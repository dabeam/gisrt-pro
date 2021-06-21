<template>
  <div class="wrap">
    <swiper :options="swiperOption" ref="mySwiper">
    <swiper-slide>
      <img class="swiper-img" src="https://imgs.qunarzz.com/vs_ceph_vcimg/79faa5a73731e84a7731db49d5baa91e.jpeg" />
    </swiper-slide>
    <swiper-slide>
      <img class="swiper-img" src="https://imgs.qunarzz.com/vs_ceph_vcimg/c0a60fa20379efa4f02ce527a680dc1b.jpeg" />
    </swiper-slide>
    <div class="swiper-pagination"  slot="pagination"></div>
  </swiper>
  </div>
</template>

<script>
  export default {
    name: 'HomeSwiper',
    data () {
      return {
        notNextTick: true,
        swiperOption: {
          pagination : '.swiper-pagination',
          loop: true
        }
      }
    }
  }
</script>

<style lang="stylus" scoped>
  .wrap >>> .swiper-pagination-bullet-active {
    background-color: #fff;
  }

  .wrap >>> .swiper-pagination-bullet {
    margin-bottom: .1rem;
  }

  .wrap {
    overflow: hidden;
    width: 100%;
    height: 2.04rem;
    height: 0;
    padding-bottom: 26.67%;
    background-color: #eee;
  }

  .wrap .swiper-img {
    width: 100%;
    height: 100%;
  }
</style>