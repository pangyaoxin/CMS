<template>
    <div>
        <img src="../../public/前端图.png" alt="">
        <h3>前端开发学习手册</h3>
        <p>2019.12.23</p>
        <base-button><slot></slot></base-button>
    </div>
</template>
<script>
import BaseButton from "./BaseButton.vue"

export default{
    name:'ContentDisplayBook',
    components:{
        BaseButton
    }
}
</script>
<style scoped>
div{
    width: 955px;
    height: 200px;
    position: relative;
    margin-bottom: 10px;
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
}
</style>