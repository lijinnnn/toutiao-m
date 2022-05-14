<template>
  <div id="app">
    <router-view />
    <h1>黑马头条</h1>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
    <van-button loading type="primary" />
    <van-button loading type="primary" loading-type="spinner" />
    <van-button loading type="info" loading-text="加载中..." />
  </div>
</template>
<script>
export default {
  name: 'App'
}
</script>
<style lang="less">
</style>
