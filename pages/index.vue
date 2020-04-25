<template>
  <div class="container">
    <div class="contants">
      <p class="title">
        Takumi's Web
      </p>
      <ul>
        <li>
          <nuxt-link to="/about">
            About
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/skills">
            Skills
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/works">
            Works
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/contact">
            Contact
          </nuxt-link>
        </li>
        <li>
          <a href="https://blog-takumin.dev/">Blog</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'top'
}
</script>

<style scoped>
.contants{
  text-align: center;
   margin: 50px;
}
.title {
  text-align: center;
}
.contants ul li{
  display: inline;
}
</style>
