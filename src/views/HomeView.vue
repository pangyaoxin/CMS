<template>
  <div class="home">
    <view-more>精选手册</view-more>
    <content-display-book>阅读</content-display-book>
    <content-display-book>阅读</content-display-book>
    <view-more>精选博客</view-more>
    <content-display-blog></content-display-blog>
    <content-display-blog></content-display-blog>
    <view-more>精选视频</view-more>
    <content-display-book>观看</content-display-book>
    <content-display-book>观看</content-display-book>
    <more-content></more-content>
  </div>
</template>

<script>
import ViewMore from "../components/ViewMore.vue"
import ContentDisplayBook from "../components/ContentDisplayBook.vue"
import ContentDisplayBlog from "../components/ContentDisplayBlog.vue"
import MoreContent from "../components/MoreContent.vue"

export default {
  name: 'HomeView',
  components: {
    ViewMore,
    ContentDisplayBook,
    ContentDisplayBlog,
    MoreContent
  }
}
</script>
