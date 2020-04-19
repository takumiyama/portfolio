<template>
  <nav class="navbar is-white" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <div class="navbar-burger" data-target="navMenu" :class="{'is-active': $store.state.isMenuActive}" @click="$store.commit('toggleMenu')">
        <span />
        <span />
        <span />
      </div>
    </div><!-- navbar-brand END -->
    <div id="navMenu" class="navbar-menu" :class="{'is-active': $store.state.isMenuActive}">
      <div class="navbar-end">
        <nuxt-link to="/about" class="navbar-item title is-3">
          About
        </nuxt-link>
        <nuxt-link to="/skills" class="navbar-item title is-3">
          Skills
        </nuxt-link>
        <nuxt-link to="/works" class="navbar-item title is-3">
          Works
        </nuxt-link>
        <nuxt-link to="/contact" class="navbar-item title is-3">
          Contact
        </nuxt-link>
        <nuxt-link to="/" class="navbar-item title is-3">
          Blog
        </nuxt-link>
      </div>
    </div><!-- navbar-menu END -->
  </nav>
</template>

<script>
export default {
  data: () => {
    return { isMenuActive: false }
  },
  methods: {
    toggleMenu () {
      this.isMenuActive = !this.isMenuActive
    }
  }
}
</script>

<style scoped>
.navbar-end {
    justify-content: flex-end;
    margin: auto;
}
</style>>
