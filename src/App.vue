<template>
  <div id="app">
    hello vue-cli

    <!-- 调用Element-ui组件 -->
    <el-row>
      <el-button type="primary">主要按钮</el-button>
    </el-row>
  </div>
</template>

<script>


export default {
  name: 'app',

  mounted(){
    //请求数据
     this.$axios.get('https://api.github.com/users').then(res => {

     })
      
  }
}
</script>

<style>
#app {

}
</style>
