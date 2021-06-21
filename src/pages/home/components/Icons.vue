<template>
  <div class="icons-wrap">
    <div class="icon-wrap">
      <swiper :options="swiperOption" ref="mySwiper">
        <swiper-slide>
          <div class="icon-box">
            <div class="icon-img-box">
              <img
                class="icon-img"
                src="//s.qunarzz.com/homenode/images/touchheader/hotel.png"
              />
            </div>
            <p class="icon-desc">酒店</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="icon-box">
            <div class="icon-img-box">
              <img
                class="icon-img"
                src="//s.qunarzz.com/homenode/images/touchheader/hotel.png"
              />
            </div>
            <p class="icon-desc">酒店</p>
          </div>
        </swiper-slide>
        <div class="swiper-pagination" slot="pagination"></div>
    </swiper>
    </div>
    
  </div>
</template>

<script>
export default {
  name: "HomeIcons",
  data() {
    return {
      notNextTick: true,
      swiperOption: {
        pagination: ".swiper-pagination",
        loop: true,
      },
    };
  },
};
</script>

<style lang="stylus" scoped>
.icons-wapper {
  width: 100%;
  height: 0;
  padding-bottom: 50%;
  background-color: #eee;
}

.icons-wapper .icon-box {
  position: relative;
  float: left;
  width: 20%;
  height: 0;
  padding-bottom: 20%;
}

.icons-wapper .icon-box .icon-img-box {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0.44rem;
}

.icons-wapper .icon-box .icon-img-box .icon-img {
  display: block;
  height: 100%;
  margin: 0 auto;
}

.icons-wapper .icon-box .icon-desc {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  height: 0.44rem;
  line-height: 0.44rem;
  text-align: center;
  color: #212121;
}
</style>