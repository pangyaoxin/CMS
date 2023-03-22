<template>
    <div>
        <h2>
            <slot></slot>
        </h2>
        <router-link to="#">查看更多  <i class="el-icon-arrow-right"></i></router-link>
    </div>
</template>
<style scoped>
div{
    width: 955px;
    height: 50px;
    background-color: white;
    margin-bottom: 10px;
    }
h2{
    float: left;
    line-height: 50px;
    margin-left: 25px;
    }
a{
    float: right;
    line-height: 50px;
    margin-right: 25px;
    color: #808080;
    }
</style>