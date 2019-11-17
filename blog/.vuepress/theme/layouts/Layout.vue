<template>
  <div>
    <BaseListLayout v-if="$pagination"/>
    <Content v-else/>
    <BackToTop></BackToTop>
  </div>
</template>
<script>
  import BaseListLayout from '@theme/components/BaseListLayout'

  export default {
    components: { BaseListLayout, },
  }
</script>

<style src="prismjs/themes/prism-okaidia.css"></style>
