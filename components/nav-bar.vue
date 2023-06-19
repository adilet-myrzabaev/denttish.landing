<template>
  <div class="px-4">
    <header class="flex justify-between items-center py-4 border-bottom-2 border-gray:50">
      <div class="flex items-center">
        <img src="/layout/images/лого.svg" alt="logo">
        <h1 class="logo-title">
          DentTish
        </h1>
      </div>
      <Menubar class="navbar-menu" :model="items" />
      <Button class="btn btn-primary">
        Войти в систему
      </Button>
    </header>
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'Denttish'
})
const items = ref([
  {
    label: 'Home',
    activeClass: 'active'
  },
  {
    label: 'Features',
    activeClass: ''
  },
  {
    label: 'Projects',
    activeClass: ''
  },
  {
    label: 'Contact',
    activeClass: ''
  }
])
</script>

<style scoped>

</style>
