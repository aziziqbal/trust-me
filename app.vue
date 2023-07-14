<template>
  <div>
    <NuxtLoadingIndicator />
    <NuxtPage />
  </div>
</template>

<script>
export default {
  setup () {
    useHead ({
      bodyAttrs: {
        class: 'nomargin'
      }
    })
  }
}
</script>

<style>
.nomargin {
  margin: 0 auto !important;
}
</style>
