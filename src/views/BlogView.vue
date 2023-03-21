<template>
    <div class="blog">
        <learning-manual></learning-manual>
        <learning-manual></learning-manual>
        <learning-manual></learning-manual>
        <learning-manual></learning-manual>
        <learning-manual></learning-manual>
        <content-paging></content-paging>
    </div>
</template>
<script>
import LearningManual from "../components/LearningManual.vue"
import ContentPaging from "../components/ContentPaging.vue"

export default {
  name: 'BlogView',
  components: {
    LearningManual,
    ContentPaging
  }
}
</script>