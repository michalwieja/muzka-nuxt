<template>
  <header :class="{ 'active': scrollPos > 0 || isActiveRoute }" class="header">
    <div class="wrapper">
      <div class="logo" @click="navActive = false">
        <NuxtLink to="/">
          <img class="logo-img" src="~/assets/img/logo.png">
        </NuxtLink>
      </div>
      <nav class="nav">
        <div :class="{ 'nav-active': navActive }" class="nav__links">
          <div v-for="link in menuLinks" :key="link.name" @click="navActive = false">
            <NuxtLink :to="link.path" class="nav__link">
              {{ link.name }}
            </NuxtLink>
          </div>
        </div>
        <div :class="{ toggle: navActive }" class="burger" @click="handleBurgerClick">
          <div class="burger__line" />
          <div class="burger__line" />
          <div class="burger__line" />
        </div>
      </nav>
    </div>
  </header>
</template>
<script>

import menuLinks from '../config/menu.js'

export default {
  name: 'Header',
  props: {
    transparent: {
      type: Boolean,
      default: false
    }
  },
  data() {
    return {
      menuLinks,
      scrollPos: 0,
      navActive: false
    }
  },
  computed: {
    isActiveRoute() {
      console.log(this.$route.path);
      const activeRoutes = ['/onas', '/kontakt', '/muzykoterapia'];
      return activeRoutes.includes(this.$route.path);
    },
  },


  destroyed() {
    window.removeEventListener('scroll', this.handleScroll)
  },

  mounted() {
    window.addEventListener('scroll', this.handleScroll)
  },
  methods: {
    handleBurgerClick() {
      this.navActive = !this.navActive
    },
    handleScroll() {
      this.scrollPos = window.scrollY
    }
  }
}
</script>
