<script setup lang='ts'>
import NavBar from '../components/Nav-Bar.vue'
import Footer from '../components/footer-down.vue'
import { useThemeStore } from '~/stores'
const themeStore = useThemeStore()
</script>

<template>
  <div>
    <Link rel="stylesheet" :href="themeStore.link || 'https://cdn.jsdelivr.net/npm/primevue@3.50.0/resources/themes/saga-blue/theme.css'" />
    <nav-bar class="mb-8" />
    <slot />
    <Footer />
  </div>
</template>

<style lang="scss" scoped></style>
