<template>
  <div id="app">
    <header>
      <home-header></home-header>
    </header>
    <main>
      <router-view></router-view>
      <section>
        <home-section></home-section>
      </section>
      <footer>
      <home-footer></home-footer>
    </footer>
    </main>
    <div class="returnTop">
      <return-top></return-top>
    </div>
  </div>
</template>

<script>
// 引入组件
import HomeHeader from "./components/HomeHeader.vue"
import HomeSection from "./components/HomeSection.vue"
import HomeFooter from "./components/HomeFooter.vue"
import ReturnTop from "./components/ReturnTop.vue"


export default {
  name:"app",
  components:{
    HomeHeader,
    HomeSection,
    HomeFooter,
    ReturnTop,
}
}
</script>

<style scoped>
  main{
    width: 1260px;
    margin: auto;
    margin-top: 15px;
    position: relative;
  }
  section{
    background-color: aqua;
    position: absolute;
    top: 0;
    right: 0;
  }
  footer{
    position: absolute;
    top: 510px;
    right: 0;
  }
  .returnTop{
    width: 42px;
    height: 172px;
    position: sticky;
    left: 85%;
    bottom: 75px;
    z-index: 10;
  }
</style>
