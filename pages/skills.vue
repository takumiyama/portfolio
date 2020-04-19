<template>
  <div class="card">
    <div class="card-content">
      <h3 class="title is-3">
        Skills
      </h3>
      <div class="content">
        <div class="content-item">
          <p class="title is-4 has-text-info">
            Backend
          </p>
          <p>
            PHP / ZendFramework / Java8 / Springboot<br>
            Mybatis / Mysql / Oracle / Postgres
          </p>
        </div>
        <div class="content-item">
          <p class="title is-4 has-text-info">
            Frontend
          </p>
          <p>
            HTML / CSS / JavaScript<br>
            Vue.js / Nuxt.js / jQuery
          </p>
        </div>
        <div class="content-item">
          <p class="title is-4 has-text-info">
            Another
          </p>
          <p>
            Linux / CentOS / WindowsOS<br>
            GCP / Vagrant / VMware<br>
            Nginx / Apache<br>
            CircleCI / Screwdriver / Chef / Ansible<br>
            zsh / bash<br>
            Illustrator / Photoshop
          </p>
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
