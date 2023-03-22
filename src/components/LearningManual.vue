<template>
    <div class="learningManual">
        <img src="../../public/前端图.png" alt="" class="showImg">
        <h2>前端开发手册</h2>
        <p>很多零基础的同学在学习前端开发的过程中，总是会迷失在繁杂的知识体系当中。</p>
        <read-button class="read-button">阅读</read-button>
        <div class="line">
        </div>
    </div>
</template>
<script>
import ReadButton from "./ReadButton.vue"

export default {
  components:{
    ReadButton
}
}
</script>
<style scoped>
.learningManual{
    width: 955px;
    height: 170px;
    background-color: white;
    margin-bottom: 10px;
    position: relative;
}
.showImg{
    width: 230px;
    height: 150px;
    position: absolute;
    left: 20px;
    bottom: 0;
}
h2{
    font-size: 18px;
    position: absolute;
    left: 275px;
    top:30px;
}
p{
    font-size: 16px;
    position: absolute;
    left: 275px;
    top:68px;
    color: #808080;
}
.line{
    width: 655px;
    height: 1px;
    background-image: url("../../public/线.png");
    position: absolute;
    left: 275px;
    bottom: 0;
}
.read-button{
    position: absolute;
    left: 275px;
    bottom: 16px;
}
</style>