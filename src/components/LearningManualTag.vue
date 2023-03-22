<!-- 学习手册组件 + 一个透明标签 -->
<template>
    <div class="learningManuaTag">
        <learning-manual></learning-manual>
        <div class="transparentTag">
            <transparent-tag>前端</transparent-tag>
        </div>
    </div>
</template>
<script>
import LearningManual from "../components/LearningManual.vue"
import TransparentTag from "../components/TransparentTag.vue"

export default {
  components: {
    LearningManual,
    TransparentTag
  }
}
</script>
<style scoped>
.learningManuaTag{
    position: relative;
}
.transparentTag{
    position: absolute;
    left: 8px;
    bottom: 9px;
}
</style>