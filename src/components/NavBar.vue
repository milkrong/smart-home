<template>
    <div class="nav-bar">
        <el-menu 
        mode="horizontal" 
        default-active="home"
        background-color = "#ff7400" 
        text-color="#fff"
        active-text-color="#fff"
        router="router"
        class="main-menu">
        <el-menu-item index="home" route="/" class="menu-item">
          <i class="el-icon-house"></i>
          主页
        </el-menu-item>
      </el-menu>
    </div>
</template>

<script>
export default {
    name: 'navBar',
    data () {
        return {
            router: true
        }
    }
}
</script>

<style scoped>
.main-menu {
    border-radius: 0.3em !important;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19) !important;
}

.menu-item {
    margin : 0px 20px !important;
}
</style>