<template>
  <div class="m-header">
    <router-link to="/user"
                 class="mine"
                 tag="div">
      <i class="iconfont icon-list"></i>
    </router-link>
    <router-link to="/search"
                 class="search"
                 tag="div">
      <i class="iconfont icon-search"></i>
      搜索
    </router-link>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '~common/scss/variable.scss';

.m-header {
  position: relative;
  height: 44px;
  width: 100%;
  text-align: center;
  background: $color-theme;
  .text {
    line-height: 44px;
    font-weight: bold;
    color: $color-text-l;
    letter-spacing: 3px;
  }
  .mine {
    position: absolute;
    top: -1.5px;
    right: 0;
    .iconfont {
      display: block;
      padding: 11px;
      font-size: 22px;
      color: $color-theme-l;
    }
  }
  .search {
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    margin: auto;
    width: 250px;
    height: 24px;
    background: $color-search;
    border-radius: 5px;
    text-align: center;
    color: $color-text-l;
    font-size: $font-size-small-x;
    .iconfont {
      display: inline-block;
      font-size: 14px;
      padding-top: 6px;
      color: $color-theme-l;
    }
  }
}
</style>
