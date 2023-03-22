<template>
    <div class="blog">
      <content-display-blog>阅读</content-display-blog>
      <tag-transparent class="tag-transparent">前端</tag-transparent>
    </div>
</template>
<script>
import ContentDisplayBlog from "../components/ContentDisplayBlog.vue"
import TagTransparent from "../components/TagTransparent.vue"


export default {
  name: 'BlogView',
  components: {
    ContentDisplayBlog,
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