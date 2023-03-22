<!-- 透明的标签 -->
<template>
    <div>
        <p>
            <slot></slot>
        </p>
    </div>
</template>
<style scoped>
    div{
        width: 58px;
        height: 30px;
        border-radius: 5px;
        background-image: url("../../public/透明标签背景.png");
    }
    p{
        font-size: 14px;
        color: white;
        text-align: center;
        line-height: 30px;
    }
</style>