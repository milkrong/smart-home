<template>
  <div class="app">
    <header class="head">
      <nav-bar></nav-bar>
    </header>
    <div class="body">
      <router-view></router-view>
    </div>
    <footer class="foot"></footer>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar";

export default {
  name: 'app',
  components: {
    'nav-bar': NavBar
  }  
}
</script>
<style>
.app {
  font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;
}

.body {
  padding: 3em 3em;
  background-color: #ffdfba;
  height: 100vh;
}
</style>
