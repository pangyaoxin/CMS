<!-- 分页组件 -->
<template>
    <div class="contentPaging">
        <el-pagination background :pager-count="4" layout="prev, pager, next" :total="100"
        ></el-pagination>
    </div>
    
</template>

<script>
</script>

<style scoped>
    .contentPaging{
        width: 955px;
        height: 50px;
        background-color: white; 
    }
    .el-pagination{
        width: 270px;
        height: 28px;
        margin: auto;
        padding-top: 11px;
    }
</style>