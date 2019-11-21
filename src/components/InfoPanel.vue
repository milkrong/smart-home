/* eslint-disable vue/no-unused-vars */
<template>
  <div class="info-panel">
      <el-row v-for="card in cards" :key="card.index">
          <el-col :span="24">
              <info-card :card="card"></info-card>
          </el-col>
      </el-row>
  </div>
</template>

<script>
import infoCard from '@/components/infoCard';

export default {
    name: 'info-panel',
    components: {
        "info-card": infoCard
    },
    data () {
        return {
            cards: [
                {
                    title: "Time and Date",
                    data: "2019-10-10"
                },
                {
                    title: "Monthly Spent",
                    data: "2000"
                },
                {
                    title: "Electrical Usage",
                    data: "1.45"
                }
            ]
        }
    }
}
</script>

<style>

</style>