<template lang="pug">
  .markdown-page
    div(v-html="markdown")
</template>

<script>
export default {
  props: ['markdown']
}
</script>
