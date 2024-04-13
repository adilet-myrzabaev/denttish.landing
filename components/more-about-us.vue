<template>
  <div>
    <section class="px-4">
      <div class="grid">
        <div class="col-12 md:col-7" :class="newClass">
          <img :class="imgClass" src="/layout/images/more.png" alt="">
        </div>
        <div class="col-12 md:col-5 ">
          <div>
            <h2 class="caption caption--small mb-3 line-height-2">
              Хотите узнать больше про возможности DentTish для вашей стоматологии?
            </h2>
            <p class="description description--middle description--middle-gray mb-5">
              Оставьте заявку для бесплатной онлайн-презентации
            </p>
            <form class="form" action="">
              <InputText placeholder="Имя" />
              <InputNumber placeholder="Телефон" />
              <InputText placeholder="Email" />
            </form>
            <Button class="btn btn-link btn-link--gray" @click="visible = true">
              <span class="btn-link__caption">Отправить заявку</span>
              <div class="bg-link bg-link--blue">
                <img class="bg-link__img" src="/layout/images/Arrow-white.svg" alt="">
              </div>
            </Button>
          </div>
        </div>
      </div>
    </section>
    <Dialog
      v-model:visible="visible"
      modal
      header="Оставить заявку"
      :style="{ width: '50rem' }"
      class="main-dialog"
    >
      <div class="grid mt-2 border-top-1 pt-5">
        <div class="col-12 md:col-6 pl-0">
          <form class="form form--tariff">
            <InputText class="w-full" placeholder="Имя" />
          </form>
        </div>
        <div class="col-12 md:col-6 pr-0 pl-0 md:pl-2">
          <form action="" class="form form--tariff">
            <InputNumber placeholder="Телефон" />
          </form>
        </div>
        <div class="col-12 px-0">
          <form action="" class="form form--tariff">
            <InputText type="email" placeholder="Email" />
          </form>
        </div>
      </div>
      <div class="flex justify-content-end gap-2">
        <Button type="button" label="Отправить" class="btn btn-primary border-round-2xl" @click="visible = false" />
      </div>
    </Dialog>
  </div>
</template>

<script setup lang="ts">
defineProps({
  // eslint-disable-next-line vue/require-default-prop
  imgClass: String,
  // eslint-disable-next-line vue/require-default-prop
  newClass: String
})
const visible = ref(false)
</script>
