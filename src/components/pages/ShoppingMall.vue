<template>
  <div>
    <div class="search-bar">
      <van-row class="test-row">
        <van-col span="3">
          <img :src="locationIcon" width="80%" class="location-icon"/>
        </van-col>
        <van-col span="16">
          <input type="text" class="search-input"/>
        </van-col>
        <van-col span="5">
          <van-button size="mini" class="search-btn">搜索</van-button>
        </van-col>
      </van-row>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ShoppingMall',
  data () {
    return {
      msg: 'data',
      locationIcon: require('../../assets/images/地图.png')
    }
  }
}
</script>

<style scoped>
  .search-bar {
    height: 1.5em;
    background-color: #e5017d;
    line-height: 1.5rem;
  }
  .search-input {
    width: 100%;
    height: 1rem;
    border-top: 0px;
    border-left: 0px;
    border-right: 0px;
    border-bottom: 1px solid #ffffff !important;
    background-color: #e5017d;
    color: #ffffff;
  }
  .location-icon {
    padding-top: 0.2rem;
    padding-left: 0.3rem;
  }
  .search-btn {
    margin-left: 0.3rem;
    width: 1.5rem;
  }
</style>
