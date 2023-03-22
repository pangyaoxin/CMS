<template>
    <div>
        <img src="../../public/前端图.png" alt="">
        <h3>前端开发学习手册</h3>
        <p class="date">2019.12.23</p>
        <p class="description">
            最近接触比较多的新手程序员和准程序员，和他们交流的过程中，我发现了一些通用问题，
            今天把这些问题整理出来，希望可以帮助更多的朋友们。
        </p>
    </div>
</template>
<script>

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
h3,p{
    position: absolute;
    left: 270px;
}
h3{
    top:35px;
    font-size: 18px;
}
p{
    font-size: 16px;
}
.date{
    top:75px;
    color: #b2b2b2;
}
.description{
    top: 107px;
    color: #666;
    padding-right: 40px;
    line-height: 30px;
}
</style>