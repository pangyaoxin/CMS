
import router from '@/router';

<template>
    <div class="homeSection">
        <img src="../../public/轮播1.png" alt="">
        <h2>精选</h2>
        <img src="../../public/线.png" alt="" class="line">
        <div class="section-selectedContent">
            <img src="../../public/前端图2.png" alt="">
            <h3>前端开发手册</h3>
            <button>阅读</button>
        </div>
        <img src="../../public/线.png" alt="" class="line">
        <router-link to="#">编程学习的五大误区</router-link>
        <img src="../../public/线.png" alt="" class="line">
        <router-link to="#">编程学习的五大误区</router-link>
        <img src="../../public/线.png" alt="" class="line">
        <router-link to="#">编程学习的五大误区</router-link>
    </div>
</template>

<script>

</script>

<style scoped>
    .homeSection{
        width: 290px;
        height: 490px;
        background-color: white;
    }
    h2,a,.section-selectedContent{
        margin-left: 22px;
    }
    h2{
        font-size: 18px;
        line-height: 47px;
    }
    /* section小精选内容 */
    .section-selectedContent{
        width: 258px;
        height: 110px;
        position: relative;
    }
    .section-selectedContent > img{
        width: 75px;
        height: 85px;
        position: absolute;
        top: 15px;
        left: 0;
    }
    .section-selectedContent > h3{
        font-size: 16px;
        position: absolute;
        left: 88px;
        top: 25px;
    }
    .section-selectedContent > button{
        width: 60px;
        height: 27px;
        position: absolute;
        left: 88px;
        bottom: 10px;
        font-size: 14px;
        color: #0084ff;
        border: none;
        border-radius: 5px;
        background-color: #e3f0fc;
    }

    a{
        font-size: 14px;
        line-height: 45px;
        color: black;
    }
    .line{
        width: 270px;
        height: 1px;
        margin-left: 10px;
        display: block;
    }
</style>