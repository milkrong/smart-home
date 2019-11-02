<template>
  <div class="home">
    <el-row type="flex" justify="space-between">
      <el-col :span="10">
        <info-panel></info-panel>
      </el-col>
      <el-col :span="10">
        Event Panel
      </el-col>
    </el-row>
  </div>
</template>

<script>
import InfoPanel from '@/components/InfoPanel';

export default {
  name: "home",
  components: {
    "info-panel": InfoPanel
  }
}
</script>

<style scoped>

</style>
