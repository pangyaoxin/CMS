<!-- 这是一个首页页眉组件 -->
<template>
    <div class="homeHeader">
        <div class="nav">
            <!-- LOGO -->
        <img src="../../public/logo.png" alt="">
        <!-- 导航栏 -->
        <div class="headerNav">
          <router-link to="/">首页</router-link>
          <router-link to="/book">学习手册</router-link>
          <router-link to="/blog">技术博客</router-link>
          <router-link to="/video">教学视频</router-link>
          <router-link to="/resources">资源下载</router-link>
        </div>
        <!-- 搜索栏 -->
        <div class="searhBar">
            <input type="search" placeholder="搜索">
            <div><i class="el-icon-search"></i></div>
        </div>
        <!-- 登录按钮 -->
        <button>登录</button>
        </div>
    </div>
</template>

<script>
export default {
  name: 'HomeHeader',
  data(){
    return{
      
    }
  },
  methods:{
  }
}
</script>

<style scoped>
/* 整个组件大盒子 */
  .homeHeader{
    width: 100%;
    height: 60px;
    background-color:white;
  }

  /* 顶部导航栏 */
  .nav{
    height: 60px;
    width: 1260px;
    margin: auto;
    display: flex;
    align-items: center;
  }
  .nav > .headerNav{
    margin-left: 25px;
  }
  .headerNav > a{
    width: 114px;
    height: 60px;
    display: inline-block;
    box-sizing: border-box;
    text-align: center;
    line-height: 60px;
    font-size: 16px;
    color: black;
  }
  /* 导航栏点击样式 */
  .router-link-exact-active{
    border-bottom: 2px solid #0084ff;
  }
  /* 搜索栏 */
  .searhBar{
    width: 300px;
    height: 40px;
    border: 1px solid #ccc;
    border-radius: 3px;   
    margin-left: 96px;    
  }
  /* 搜索栏输入框 */
  .searhBar > input{
    width: 253px;
    height: 40px;
    text-indent:10px;
    border: none;
  }
  /* 搜索栏输入框后面的搜索图标 */
  .searhBar > div{
    width: 47px;
    height: 40px;
    float: right;
    text-align: center;
  }
  .searhBar > div > i{
    font-size: 17px;
    line-height: 40px;
    color: #c4c4c4;
  }

  /* 登录按钮 */
  button{
    margin-left: 20px;
    width: 130px;
    height: 60px;
    border-bottom-right-radius:30px;
    border-bottom-left-radius:30px;
    background-color: #0084ff;
    color: white;
    font-size: 18px;
    border: none;
  }
</style>