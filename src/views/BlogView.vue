<template>
    <div class="blog">
      <content-display-blog-type-2>阅读</content-display-blog-type-2>
      <content-display-blog-type-2>阅读</content-display-blog-type-2>
      <content-display-blog-type-2>阅读</content-display-blog-type-2>
      <content-display-blog-type-2>阅读</content-display-blog-type-2>
      <content-display-blog-type-2>阅读</content-display-blog-type-2>
      <content-display-blog-type-2>阅读</content-display-blog-type-2>
      <content-paging></content-paging>
    </div>
</template>
<script>
import ContentDisplayBlogType2 from "../components/ContentDisplayBlogType2.vue"
import ContentPaging from "../components/ContentPaging.vue"

export default {
  name: 'BlogView',
  components: {
    ContentDisplayBlogType2,
    ContentPaging
  }
}
</script>