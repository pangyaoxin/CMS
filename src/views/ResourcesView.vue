<template>
    <div>
        <div class="resources">
        <h2>资源下载</h2>
        <div class="line"></div>
    </div>
        <download-resources></download-resources>
        <download-resources></download-resources>
    </div>
    
</template>
<script>
import DownloadResources from '@/components/DownloadResources.vue';

export default{
name:'ResourcesView',
components:{
    DownloadResources
}
}
</script>
<style scoped>
.resources{
    width: 955px;
    height: 61px;
    background-color: white;
    position: relative;
    }
h2{
    font-size: 20px;
    float: left;
    line-height: 60px;
    margin-left: 25px;
    }
.line{
    width: 915px;
    height: 1px;
    background-image: url("../../public/线.png");
    position: absolute;
    left: 20px;
    bottom: 0px;
}
</style>
