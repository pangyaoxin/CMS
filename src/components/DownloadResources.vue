<template>
    <div class="download">
        <img src="../../public/资源下载.png" alt="资源下载">
        <h3>某种资源</h3>
        <p>提取码：1234</p>
        <router-link to="#">立即下载</router-link>
        <div class="line"></div>
    </div>
</template>
<style scoped>
    .download{
        width: 955px;
        height: 106px;
        background-color: white;
        position: relative;
    }
    img,h3,p,a,.line{
        position: absolute;
    }
    img{
        width: 70px;
        height: 50px;
        left: 50px;
        top: 30px;
    }
    h3,p{
        left: 140px;
    }
    h3{
        font-size: 16px;
        top: 33px;
    }
    p{
        font-size: 14px;
        top: 63px;
        color: #808080;
    }
    a{
        font-size: 14px;
        color: #0084ff;
        right: 70px;
        top: 50px;
    }
    .line{
        width: 875px;
        height: 1px;
        background-image: url("../../public/线.png");
        left: 40px;
        bottom: 1px;
    }
</style>