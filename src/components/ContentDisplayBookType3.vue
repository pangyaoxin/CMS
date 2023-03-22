<template>
    <div class="box">
        <content-display-book-type-2>
            <slot></slot>
        </content-display-book-type-2>
        <tag-transparent class="tag-transparent">前端</tag-transparent>
    </div>
</template>
<script>
import ContentDisplayBookType2 from "../components/ContentDisplayBookType2.vue"
import TagTransparent from "../components/TagTransparent.vue"

export default{
    name:'ContentDisplayBookType3',
    components:{
        ContentDisplayBookType2,
        TagTransparent
    }
}
</script>
<style scoped>
div{
    position: relative;
}
.tag-transparent{
    position: absolute;
    left: 23px;
    bottom: 33px;
}
</style>