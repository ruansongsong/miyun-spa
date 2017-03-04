<template>
  <div id="app">
    <swiper></swiper>

    <feed></feed>
  </div>
</template>

<script>
import swiper from './components/swiper';
import feed from './components/feed';

export default {
  components: {
    swiper,
    feed,
  },
};
</script>

<style lang="less">

@import "../style/core/reset";

</style>
