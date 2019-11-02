/* eslint-disable vue/no-unused-vars */
<template>
  <div class="info-panel">
      <el-row v-for="title in cardTitles" :key="title.index">
          <el-col :span="24">
          </el-col>
      </el-row>
  </div>
</template>

<script>
export default {
    name: 'info-panel',
    data () {
        return {
            cardTitles: ['Time and Date', 'Monthly Spent', 'Eletrical Usage']
        }
    }
}
</script>

<style>

</style>