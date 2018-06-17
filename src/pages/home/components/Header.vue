<template>
  <div class="header">
    <div class="header-left">
      <span class="iconfont">&#xe624;</span>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      <input />
    </div>
    <div class="header-right">
      <span>城市</span>
      <span class="iconfont">&#xe64a;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang='stylus' scoped>
  .header
    display: flex
    line-height: 0.86rem
    background: #00bcd4
    .header-left
      width: 0.4rem
    .header-input
      flex: 1
      justify-content: flex-start
</style>
