<template>
  <div class="card">
    <div class="card-content">
      <h3 class="title is-3">
        About
      </h3>
      <div class="media content-item">
        <div class="media-left">
          <figure class="image is-64x64">
            <img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
          </figure>
        </div>
        <div class="media-content">
          <p class="title is-4">
            Takumi
          </p>
          <p class="subtitle is-6">
            WebEngineer / ITConsultant
          </p>
        </div>
      </div>

      <div class="content">
        <div class="content-item">
          <p class="title is-4 has-text-info">
            Profile
          </p>
          <p>
            2013年4月に大手Web会社に入社。そこから社内SEの開発部隊としてWebEngineerとしてのキャリアスタート。<br>
            約8年間エンジニアリングを経験し、現在はITコンサルタントへキャリアチェンジ。個人で開発を行っています。<br>
            前職では主にPHP、Java8（springboot）でのバックエンド開発、nuxt.jsでのフロントエンド開発、CICDなどの環境構築を行っていました。<br>
            趣味は、サッカー/フットサルをやることです。学生時代10年間サッカー部に所属していました。
          </p>
        </div>
        <div class="content-item">
          <p class="title is-4 has-text-info">
            History
          </p>
          <div class="timeline">
            <header class="timeline-header">
              <span class="tag is-primary">1991</span>
            </header>
            <div class="timeline-item">
              <div class="timeline-marker" />
              <div class="timeline-content">
                <p class="heading">
                  March 1991
                </p>
                <p>青森県青森市で生まれる</p>
              </div>
            </div>
            <header class="timeline-header">
              <span class="tag is-primary">2009</span>
            </header>
            <div class="timeline-item">
              <div class="timeline-marker" />
              <div class="timeline-content">
                <p class="heading">
                  April 2009
                </p>
                <p>
                  北海道の大学へ進学し情報デザインを学ぶ
                </p>
              </div>
            </div>
            <header class="timeline-header">
              <span class="tag is-primary">2013</span>
            </header>
            <div class="timeline-item">
              <div class="timeline-marker" />
              <div class="timeline-content">
                <p class="heading">
                  April 2013
                </p>
                <p>
                  上京。大手Web会社の社内SEとして働き始める
                </p>
              </div>
            </div>
            <header class="timeline-header">
              <span class="tag is-primary">2020</span>
            </header>
            <div class="timeline-item">
              <div class="timeline-marker" />
              <div class="timeline-content">
                <p class="heading">
                  April 2020
                </p>
                <p>
                  転職。外資コンサル会社でITコンサルへキャリアチェンジ
                </p>
              </div>
            </div>
            <div class="timeline-header">
              <span class="tag is-primary">Now</span>
            </div>
          </div>
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
@import '~/node_modules/bulma-extensions/bulma-timeline/dist/css/bulma-timeline.min.css';
.card {
    margin: 20px;
}
.content-item {
    margin-bottom: 30px;
    margin-left: 30px;
}
</style>
