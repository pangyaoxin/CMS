<template>
  <div>
    <div class="book">
      <content-display-book-type-2>阅读</content-display-book-type-2>
      <content-display-book-type-2>阅读</content-display-book-type-2>
      <content-display-book-type-2>阅读</content-display-book-type-2>
      <content-display-book-type-2>阅读</content-display-book-type-2>
      <content-display-book-type-2>阅读</content-display-book-type-2>
    </div>
    <more-content></more-content>
  </div>
</template>

<script>
import ContentDisplayBookType2 from "../components/ContentDisplayBookType2.vue"
import MoreContent from "../components/MoreContent.vue"

export default {
  name: 'BookView',
  components: {
    ContentDisplayBookType2,
    MoreContent
  }
}
</script>

<style scoped>
.book{
  margin-bottom: 10px;
}
</style>