<template>
  <div id="app">
  <!--路由管道标签，任何符合某一路由(route)信息的组件都会在这个标签内展示出来 -->
  <p>test</p>
  <router-view></router-view>
  <p>test</p>
  <router-link v-bind:to="'/param'">Param Link</router-link>
  <router-link v-bind:to="'/param'">param</router-link>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>
<!-- css格式 -->
<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
