<template>
  <div class="card">
    <div class="card-content">
      <h3 class="title is-3">
        Works
      </h3>
      <div class="content">
        <div class="content-item">
          <p class="title is-4 has-text-info">
            Business Develop
          </p>
          <ul>
            <li>勤怠管理システム</li>
            <li>業績評価システム</li>
            <li>eラーニングシステム</li>
            <li>予約管理システム</li>
          </ul>
        </div>
        <div class="content-item">
          <p class="title is-4 has-text-info">
            Personal Develop
          </p>
          <ul>
            <li>Portfolio</li>
            <li><a href="">blog</a></li>
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
