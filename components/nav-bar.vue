<template>
  <div class="px-4">
    <header class="flex justify-between items-center py-4 sm:border-bottom-2 sm:border-gray:50">
      <div class="flex items-center">
        <Menubar class="navbar-menu flex md:hidden" :model="items" />
        <img class="logo-img" src="/layout/images/logo.svg" alt="logo">
        <h1 class="logo-title">
          DentTish
        </h1>
      </div>
      <Menubar class="navbar-menu hidden md:flex" :model="items" />
      <Button class="btn btn-primary flex" @click="signInSystem">
        Войти <span class="hidden md:flex">в систему</span>
      </Button>
    </header>
  </div>
</template>

<script setup lang="ts">
const router = useRouter()

useHead({
  title: 'Denttish | Docs'
})
const items = ref([
  {
    label: 'Домой',
    activeClass: 'active',
    command: () => {
      router.push('/')
    }
  },
  {
    label: 'Тур в системе',
    activeClass: '',
    command: () => {
      router.push('/systemTour')
    }
  },
  {
    label: 'Цена',
    activeClass: '',
    command: () => {
      router.push('/prices')
    }
  },
  {
    label: 'Поддержка',
    activeClass: '',
    command: () => {
      router.push('/support')
    }
  }
])
const signInSystem = () => {
  window.open('https://denttish.dev/')
}
</script>

<style scoped>

</style>
