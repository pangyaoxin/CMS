<template>
  <div>
    <div class="video">
      <content-display-book-type-3>观看</content-display-book-type-3>
      <content-display-book-type-3>观看</content-display-book-type-3>
      <content-display-book-type-3>观看</content-display-book-type-3>
      <content-display-book-type-3>观看</content-display-book-type-3>
      <content-display-book-type-3>观看</content-display-book-type-3>
    </div>
      <more-content></more-content>
  </div>
</template>
<script>
import ContentDisplayBookType3 from "../components/ContentDisplayBookType3.vue"
import MoreContent from "../components/MoreContent.vue"

export default {
  name: 'VideoView',
  components: {
    ContentDisplayBookType3,
    MoreContent,
  }
}
</script>
<style scoped>
.video{
  margin-bottom: 10px;
}
</style>