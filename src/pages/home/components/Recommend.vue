<template>
  <div>
    <div class="recommend-title">
      <span class="iconfont icon-heart">&#xe60f;</span>
      猜你喜欢
    </div>
    <ul>
      <li class="list-item">
        <div class="item-img">
          <img src="http://img1.qunarzz.com/sight/p0/1905/96/964c82d07da59e1aa3.img.jpg_200x200_836c68de.jpg" alt="太阳马戏 《X 绮幻之境》" />
        </div>
        <div class="item-img-tag">可订今日</div>
        <div class="item-info">
          <div class="inner-box">
            <div class="info-title"></div>
            <div class="info-commend"></div>
            <div class="info-price"></div>
          </div>
        </div>
      </li>
    </ul>
  </div>
  
</template>

<script>
export default {
  name: 'HomeRecommend'
}
</script>

<style lang="stylus" scoped>
div {
  box-sizing: border-box;
  }
.recommend-title {
  width: 100%;
  height: .8rem;
  line-height: .8rem;
  font-size: .32rem;
  background-color: #eee;
  padding: 0 .2rem;
}

.recommend-title .icon-heart {
  color: rgb(255,102,77);
}

.list-item {
  position: relative;
  display: flex;
  width: 100%;
  height: 2.4rem;
}
.list-item .item-img {
  width: 2.4rem;
  height: 2.4rem;
  background-color: green;
  padding: .2rem;
}

.list-item .item-img img {
  width: 100%;
  height: 100%;
}
.list-item .item-img-tag {
  position: absolute;
  top: .2rem;
  left: .2rem;
  width: 1.02rem;
  height: .38rem;
  line-height: .38rem;
  background-image: url(https://img1.qunarzz.com/piao/fusion/1802/20/2ba6d10b17972e02.png);
  background-size: 100% 100%;
  font-size: .2rem;
  color: #fff;
  text-indent: .04rem;
}

.list-item .item-info {
  flex: 1;
  padding: .4rem .1rem;
  background-color: blue;
}

.list-item .item-info .inner-box {
  width: 100%;
  height: 100%;
}
</style>