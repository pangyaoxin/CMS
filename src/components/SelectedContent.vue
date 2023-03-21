<template>
    <div class="selectedContent">
        <!-- 精选内容标题 -->
        <div class="contentTitle">
            <h2>精选内容</h2>
            <router-link to="#">查看更多  <i class="el-icon-arrow-right"></i></router-link>
        </div>
        <!-- 精选内容展示1 -->
        <div class="contentShow">
            <img src="../../public/前端图.png" alt="">
            <h3>前端开发学习手册</h3>
            <p>2019.12.23</p>
            <button>阅读</button>
        </div>
        <!-- 精选内容展示1 -->
        <div class="contentShow">
            <img src="../../public/前端图.png" alt="">
            <h3>前端开发学习手册</h3>
            <p>2019.12.23</p>
            <button>阅读</button>
        </div>
    </div>
</template>
<script>
// import ReadButton from "./components/ReadButton.vue"

</script>
<style scoped>
    .selectedContent{
        width: 955px;
        height: 480px;
        display: flex;
        flex-direction:column;
    }
    /* 标题部分 */
    .contentTitle{
        width: 100%;
        height: 50px;
        background-color: white;
        margin-bottom: 10px;
    }
    .contentTitle > h2{
        float: left;
        line-height: 50px;
        margin-left: 25px;
    }
    .contentTitle > a{
        float: right;
        line-height: 50px;
        margin-right: 25px;
        color: #808080;
    }
    /* 内容展示部分 */
    .contentShow{
        width: 955px;
        height: 200px;
        position: relative;
        margin-bottom: 10px;
        background-color: white;
    }
    .contentShow > img{
        width: 230px;
        height: 150px;
        position: absolute;
        left: 15px;
        top: 25px;
    }
    .contentShow > h3,p,button{
        position: absolute;
        left: 270px;
    }
    .contentShow > h3{
        top:35px;
        font-size: 18px;
    }
    .contentShow > p{
        top:75px;
        font-size: 16px;
    }
    .contentShow > button{
        width: 90px;
        height: 40px;
        top:120px;
        font-size: 14px;
        color: #0084ff;
        border: none;
        border-radius: 5px;
        background-color: #e3f0fc;
    }
</style>