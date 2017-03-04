<template>
<div id="feed">
  <tab>
    <tabItem >孕期知识</tabItem>
    <tabItem>胎儿发育</tabItem>
    <tabItem>营养中心</tabItem>
    <tabItem>自然分娩</tabItem>
  </tab>
  <div class="feed">
    <a href="https://www.baidu.com" class="feed-item">
      <p class="feed-item-title">营养均衡即可别贪多</p>
      <img src="" alt="" class="feed-item-img">
    </a>
    <a href="#" class="feed-item">
      <p class="feed-item-title">营养均衡即可别贪多</p>
      <img src="" alt="" class="feed-item-img">
    </a>
  </div>
  </div>
</template>

<script>
import tab from './tab/tab';
import tabItem from './tab/tab-item';

export default {
  data() {
    return {
      list: [
        '233',
        '23333',
      ],
    };
  },
  components: {
    tab,
    tabItem,
  },
};
</script>

<style lang="less">
@import '../../style/components/feed';
</style>
