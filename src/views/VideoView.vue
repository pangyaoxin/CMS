<template>
    <div class="video">
        <learning-manual-tag></learning-manual-tag>
        <more-content></more-content>
    </div>
</template>
<script>
import LearningManualTag from "../components/LearningManualTag.vue"
import MoreContent from "../components/MoreContent.vue"

export default {
  name: 'VideoView',
  components: {
    LearningManualTag,
    MoreContent,
  }
}
</script>
<style scoped>
</style>