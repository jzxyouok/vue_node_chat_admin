<template>
  <div id="app">
      <el-row :gutter="20">
        <el-col :span="6"><div class="mydiv">1</div></el-col>
        <el-col :span="6"><div class="mydiv">1</div></el-col>
        <el-col :span="6"><div class="mydiv">1</div></el-col>
        <el-col :span="6"><div class="mydiv">1</div></el-col>
      </el-row>
  </div>
</template>

<script>
import Hello from './components/Hello'

export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.mydiv {
  background-color: #fc9;
}
</style>
