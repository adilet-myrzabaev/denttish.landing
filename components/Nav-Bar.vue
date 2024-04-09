<template>
  <div class="px-4">
    <header class="flex justify-between items-center py-4 border-bottom-2 border-gray:50">
      <div class="flex items-center">
        <img src="/layout/images/logo.svg" alt="logo">
        <h1 class="logo-title">
          DentTish
        </h1>
      </div>
      <Menubar class="navbar-menu" :model="items" />
      <Button class="btn btn-primary" @click="signInSystem">
        Войти в систему
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
      router.push('/tourSystem')
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
