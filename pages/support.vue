<template>
  <div>
    <section class="px-4">
      <div class="grid">
        <div class="col-12 md:col-6 pr-8">
          <img class="w-full border-round-3xl" src="/layout/images/support-banner.png" alt="">
        </div>
        <div class="col-12 md:col-6">
          <div class="h-full flex flex-column justify-center">
            <h2 class="caption caption--small mb-3 line-height-2">
              Профессиональная техническая поддержка
            </h2>
            <p class="description description--middle description--middle-gray mb-6">
              На поддержке DentTish могут быть предоставлены следующие возможности:
            </p>
            <Button class="btn btn-link" @click="visible = true">
              <span class="btn-link__caption">Задайте вопрос поддержки</span>
              <div class="bg-link bg-link--aqua">
                <img class="bg-link__img" src="/layout/images/Arrow-black.svg" alt="">
              </div>
            </Button>
          </div>
        </div>
      </div>
      <Dialog
        v-model:visible="visible"
        modal
        header="Вопрос поддержки"
        class="main-dialog w-4rem sm:w-30rem"
      >
        <div class="grid mt-2 border-top-1 pt-5">
          <div class="col-12 md:col-6 pl-0">
            <form class="form form--tariff">
              <InputText class="w-full" placeholder="Имя" />
            </form>
          </div>
          <div class="col-12 md:col-6 pr-0">
            <form action="" class="form form--tariff">
              <InputText placeholder="Электронная почта" />
            </form>
          </div>
          <div class="col-12 px-0">
            <form action="" class="form form--tariff">
              <InputText placeholder="Ваш запрос" />
            </form>
          </div>
        </div>
        <div class="flex justify-content-end gap-2">
          <Button type="button" label="Отправить" class="btn btn-primary border-round-2xl" @click="visible = false" />
        </div>
      </Dialog>
    </section>
    <section class="px-4">
      <div class="grid">
        <div class="col-12 md:col-4">
          <div class="card card--support justify-content-start">
            <img src="/layout/icons/headphones-icon.svg" alt="">
            <h4 class="caption caption--support">
              Техническая Поддержка:
            </h4>
            <p class="description description--support">
              Обеспечение помощи в решении технических вопросов, связанных с использованием DentTish, включая устранение возможных ошибок и неполадок.
            </p>
          </div>
        </div>
        <div class="col-12 md:col-4">
          <div class="card card--support justify-content-start">
            <img src="/layout/icons/clock-24-icon.svg" alt="">
            <h4 class="caption caption--support ">
              Онлайн обучение
            </h4>
            <p class="description description--support">
              Записанные видео уроки по использованию системы которые вы можете просмотреть в любое удобное для вас время
            </p>
          </div>
        </div>
        <div class="col-12 md:col-4">
          <div class="card card--support justify-content-start">
            <img src="/layout/icons/tv-code-icon.svg" alt="">
            <h4 class="caption caption--support">
              Консультации по Функционалу:
            </h4>
            <p class="description description--support">
              Поддержка в понимании и использовании различных функций DentTish, в том числе консультации по настройке и индивидуальным настройкам по предворительной заявке
            </p>
          </div>
        </div>
      </div>
    </section>
    <more-about-us />
    <section class="px-4">
      <div class="grid">
        <div class="col-12 md:col-3">
          <div class="card card--support">
            <img src="/layout/icons/Instagram-blue-icon.svg" alt="">
            <h4 class="caption caption--support caption--support-darkblue">
              DentTish Dev
            </h4>
            <p class="description--support description--support-small">
              Свежые новости и акции в инстаграме посмотрите и подпишитесь
            </p>
            <Button class="btn btn-link btn-link--aqua">
              <span class="btn-link__caption">Посмотреть</span>
              <div class="bg-link bg-link--blue">
                <img class="bg-link__img" src="/layout/images/Arrow-white.svg" alt="">
              </div>
            </Button>
          </div>
        </div>
        <div class="col-12 md:col-3">
          <div class="card card--support">
            <img src="/layout/icons/whatsapp-blue-icon.svg" alt="">
            <h4 class="caption caption--support caption--support-darkblue">
              +996553 871 595
            </h4>
            <p class="description--support description--support-small">
              Задать прямой вопрос тех поддержке
            </p>
            <Button class="btn btn-link btn-link--aqua">
              <span class="btn-link__caption">Написать</span>
              <div class="bg-link bg-link--blue">
                <img class="bg-link__img" src="/layout/images/Arrow-white.svg" alt="">
              </div>
            </Button>
          </div>
        </div>
        <div class="col-12 md:col-3">
          <div class="card card--support">
            <img src="/layout/icons/youtube-blue-icon.svg" alt="">
            <h4 class="caption caption--support caption--support-darkblue">
              DentTish Dev
            </h4>
            <p class="description--support description--support-small">
              Наши видео уроки
            </p>
            <Button class="btn btn-link btn-link--aqua">
              <span class="btn-link__caption">Посмотреть</span>
              <div class="bg-link bg-link--blue">
                <img class="bg-link__img" src="/layout/images/Arrow-white.svg" alt="">
              </div>
            </Button>
          </div>
        </div>
        <div class="col-12 md:col-3">
          <div class="card card--support">
            <img src="/layout/icons/tiktok-blue-icon.svg" alt="">
            <h4 class="caption caption--support caption--support-darkblue">
              DentTish Dev
            </h4>
            <p class="description--support description--support-small">
              Наши отзывы и конкурсы
            </p>
            <Button class="btn btn-link btn-link--aqua ">
              <span class="btn-link__caption">Посмотреть</span>
              <div class="bg-link bg-link--blue">
                <img class="bg-link__img" src="/layout/images/Arrow-white.svg" alt="">
              </div>
            </Button>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
import MoreAboutUs from '../components/more-about-us.vue'
const visible = ref(false)
</script>

<style scoped>
.card--support{
  .bg-link{
    width: 32px;
    height: 32px;
    & > img {
      width: 15px;
    }
  }
  .btn-link__caption{
    font-size: 14px;
    margin-right: 50px;
  }
}
</style>
