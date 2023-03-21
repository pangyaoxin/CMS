<template>
  <div class="home">
    <selected-content></selected-content>
    <selected-content></selected-content>
    <selected-content></selected-content>
    <more-content></more-content>
  </div>
</template>

<script>
import SelectedContent from "../components/SelectedContent.vue"
import MoreContent from "../components/MoreContent.vue"

export default {
  name: 'HomeView',
  components: {
    SelectedContent,
    MoreContent
  }
}
</script>
