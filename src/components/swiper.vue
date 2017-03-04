<template>
  <swiper :options="swiperOption">
    <swiper-slide><img src="../assets/swiper/swiper-1.png" alt="header"></swiper-slide>
    <swiper-slide><img src="../assets/swiper/swiper-2.png" alt="header"></swiper-slide>
    <swiper-slide><img src="../assets/swiper/swiper-3.png" alt="header"></swiper-slide>
    <div class="swiper-pagination" slot="pagination"></div>
  </swiper>
</template>

<script>
// 引入 swiper 模块
// import Vue from 'vue';
import { swiper, swiperSlide } from 'vue-awesome-swiper';

export default {
  data() {
    return {
      swiperOption: {
        pagination: '.swiper-pagination',
        paginationClickable: true,
        // autoplay: 3000,
      },
    };
  },
  components: {
    swiper,
    swiperSlide,
  },
};
</script>

<style lang="less">
@import '../../style/core/index';
  img {
    width: 100%;
  }
  .swiper-pagination-bullet-active {
    background: #EABDB7 !important;
  }
</style>
