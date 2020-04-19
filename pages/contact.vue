<template>
  <div class="card">
    <div class="card-content">
      <h3 class="title is-3">
        Contact
      </h3>
      <div class="content">
        <div class="content-item">
          <p class="title is-4 has-text-info">
            Account
          </p>
          <span>以下からご連絡ください。</span>
          <ul>
            <li><a href="https://github.com/takumiyama">GitHub</a></li>
            <li><a href="https://www.facebook.com/takumi.okayama">Facebook</a></li>
            <li><a href="mailto:takumi.oka.03.11@gmail.com">Mail</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
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
.content-item {
    margin-bottom: 30px;
    margin-left: 30px;
}
</style>
