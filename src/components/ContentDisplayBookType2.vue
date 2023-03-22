<template>
    <div class="box">
        <img src="../../public/前端图.png" alt="">
        <h3>前端开发学习手册</h3>
        <p class="description">
            很多零基础的同学在学习前端开发的过程中，总是会迷失在繁杂的知识体系当中。
        </p>
        <base-button><slot></slot></base-button>
        <div class="line"></div>
    </div>
</template>
<script>
import BaseButton from "./BaseButton.vue"

export default{
    name:'ContentDisplayBookType2',
    components:{
        BaseButton
    }
}
</script>
<style scoped>
.box{
    width: 955px;
    height: 200px;
    position: relative;
    background-color: white;
}
img{
    width: 230px;
    height: 150px;
    position: absolute;
    left: 15px;
    top: 25px;
}
h3,p,button{
    position: absolute;
    left: 270px;
}
h3{
    top:35px;
    font-size: 18px;
}
p{
    top:75px;
    font-size: 16px;
    color: #808080;
}
.line{
    width: 655px;
    height: 1px;
    background-image: url("../../public/线.png");
    position: absolute;
    left: 270px;
    bottom: 25px;
}
</style>