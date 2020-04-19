<template>
  <h2 class="subtitle is-size-4">
    Contactです
  </h2>
</template>
<script>
export default {
  fetch ({ store }) {
    store.commit('resetMenu')
  }
}
</script>

<style scoped>
.card {
    margin: 20px;
}
</style>
