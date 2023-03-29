<template>
    <div class="bookContent">
        <h1>第01节：《前端开发学习手册》概述</h1>
        <p class="collect">收藏</p>
        <div class="line"></div>
        <div class="book">
            <p class="text">这是书的内容！</p>
        </div>
    </div>
</template>
<style scoped>
.bookContent{
    width: 840px;
    /* height: 825px; */
    background-color: white;
}
.line{
    width: 820px;
    height: 1px;
    background-image: url('../../public/线.png');
}
h1,.collect,.text{
    line-height: 24px;
}
h1,.text{
    text-indent: 10px;
}
h1{
    font-size: 16px;
}
.collect{
    font-size: 16px;
    color: #b2b2b2;
}
.text{
    font-size: 14px;
}
</style>