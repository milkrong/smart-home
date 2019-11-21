<template>
    <div class="info-card">
        <el-card>
            <div slot="header">
                <span>{{ card.title }}</span>
            </div>
            {{ card.data }}
        </el-card>
    </div>
</template>

<script>
export default {
    name: 'info-card',
    props: ['card']
}
</script>

<style scoped>

</style>