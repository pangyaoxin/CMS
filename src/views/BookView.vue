<template>
  <div>
    <div class="book">
      <learning-manual></learning-manual>
      <learning-manual></learning-manual>
      <learning-manual></learning-manual>
      <learning-manual></learning-manual>
      <learning-manual></learning-manual>
    </div>
    <more-content></more-content>
  </div>
</template>

<script>
import LearningManual from "../components/LearningManual.vue"
import MoreContent from "../components/MoreContent.vue"

export default {
  name: 'BookView',
  components: {
    LearningManual,
    MoreContent
  }
}
</script>

<style scoped>
  .book{
    width: 955px;
    background-color: white;
  }
</style>