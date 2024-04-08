<template>
  <footer class="footer px-4">
    <div class="grid border-bottom-1 px-5 pb-8">
      <div class="col-12 md:col-4">
        <div class="flex items-center">
          <img src="/layout/images/logo.svg" alt="">
          <h4 class="footer__logo-title">
            DentTish
          </h4>
        </div>
        <p class="footer__logo-description mb-5">
          Управляйте улыбками с легкостью
        </p>
        <div class="flex items-center gap-4">
          <img class="cursor-pointer" src="/layout/images/tik-tok.svg" alt="">
          <img class="cursor-pointer" src="/layout/images/Facebook-icon.svg" alt="">
          <img class="cursor-pointer" src="/layout/images/Instagram-icon.svg" alt="">
          <img class="cursor-pointer" src="/layout/images/YouTube-icon.svg" alt="">
        </div>
      </div>
      <div class="col-12 md:col-8">
        <div class="grid">
          <div class="col-12 md:col-4">
            <ul class="list-menu">
              <h4 class="list-menu__caption">
                Сайт
              </h4>
              <li>
                <nuxt-link class="list-menu__description" to="">
                  О комапнии
                </nuxt-link>
              </li>
              <li>
                <nuxt-link class="list-menu__description" to="">
                  Отзывы
                </nuxt-link>
              </li>
              <li>
                <nuxt-link class="list-menu__description" to="">
                  Почему онлайн
                </nuxt-link>
              </li>
              <li>
                <nuxt-link class="list-menu__description" to="">
                  Поддержка
                </nuxt-link>
              </li>
            </ul>
          </div>
          <div class="col-12 md:col-4">
            <ul class="list-menu">
              <h4 class="list-menu__caption">
                Ссылки
              </h4>
              <li>
                <nuxt-link class="list-menu__description" to="">
                  Домой
                </nuxt-link>
              </li>
              <li>
                <nuxt-link class="list-menu__description" to="">
                  Тур в системе
                </nuxt-link>
              </li>
              <li>
                <nuxt-link class="list-menu__description" to="">
                  Цены
                </nuxt-link>
              </li>
              <li>
                <nuxt-link class="list-menu__description" to="">
                  Блог
                </nuxt-link>
              </li>
            </ul>
          </div>
          <div class="col-12 md:col-4">
            <ul class="list-menu">
              <h4 class="list-menu__caption">
                Контакт
              </h4>
              <li>
                <nuxt-link to="mailto:denttish1@gmail.com" class="list-menu__description">
                  denttish1@gmail.com
                </nuxt-link>
              </li>
              <li>
                <nuxt-link class="list-menu__description" to="tel:+996553871595">
                  +996 553 871 595
                </nuxt-link>
              </li>
              <li>
                <nuxt-link class="list-menu__description" to="">
                  Почему онлайн
                </nuxt-link>
              </li>
              <li>
                <nuxt-link class="list-menu__description" to="">
                  Поддержка
                </nuxt-link>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <p class="text-center mt-4">
      2023
    </p>
  </footer>
</template>
<script setup lang="ts">

</script>
<style scoped>

</style>
