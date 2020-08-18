<template>
  <div class="hello">
    <van-button type="primary">主要按钮</van-button>
<!--    <div class="my-test">-->
<!--      <p class="test">test</p>-->
<!--    </div>-->
  </div>
</template>

<script>

export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
/*.my-test {*/
/*  width: 20rem;*/
/*  height: 10rem;*/
/*  text-align: center;*/
/*  background-color: #42b983;*/
/*  .test {*/
/*    color: pink;*/
/*    font-size: 2rem;*/
/*  }*/
/*}*/

</style>
