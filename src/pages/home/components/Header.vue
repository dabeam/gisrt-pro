<template>
  <div class="header">
    <div class="header-left">
      <span class="iconfont">&#xe624;</span>
    </div>
    <div class="header-middle">
      <span class="iconfont search-icon">&#xe632;</span>
      <div class="kw">输入城市/景点/游玩主题</div>
      <input type="text" class="header-input" />
    </div>
    <div class="header-right">城市
      <span class="iconfont">&#xe6aa;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus"  scoped>
  .header {
    display: flex;
    width: 100%;
    height: .88rem;
    color: #fff;
    background-color: #00bcd4;
  }

  .header .header-left {
    width: .8rem;
    height: 100%;
    line-height: .88rem;
    text-align: center;
  }

  .header .header-middle {
    position: relative;
    flex: 1;
    margin: .14rem 0;
  } 
  .header .header-middle .search-icon {
    position: absolute;
    top: .13rem;
    left: .2rem;
    color: #e4e7ea;
  }

  .header .header-middle .kw {
    position: absolute;
    top: .16rem;
    left: .65rem;
    color: #e4e7ea;
  }

  .header .header-middle .header-input {
    width: 100%;
    height: 100%;
    border-radius: .06rem; 
  }

  .header .header-right {
    width: 1.32rem;
    height: 100%;
    line-height: .88rem;
    text-align: center;
  }
</style> 
