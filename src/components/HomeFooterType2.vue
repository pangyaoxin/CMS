
import router from '@/router';

<template>
    <div class="footer">
        <div class="copyrightInformation">
            <router-link to="#">晓舟报告</router-link>
            <router-link to="#">移动端</router-link>
            <router-link to="#">团队介绍</router-link>
            <p>版权内容。。。。</p>
        </div>
    </div>
</template>
<style scoped>
.footer{
    width: 100%;
    height: 60px;
    background-color: white;
}
.copyrightInformation{
    margin: auto;
    line-height: 60px;
}
a,p{
    font-size: 16px;
    color: #b2b2b2;
}
</style>