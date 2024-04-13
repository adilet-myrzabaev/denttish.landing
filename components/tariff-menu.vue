<template>
  <div>
    <section class="px-4">
      <div class="tab-menu-price">
        <h2 class="caption caption--small mb-3 line-height-2 mb-6 text-center md:text-left">
          Тарифные планы USD
        </h2>
        <div class="flex items-center justify-center md:justify-end md:mb--15 gap-6 border-[#092C4C] border-bottom-1 md:border-none pb-4 md:pb-0">
          <Button
            class="btn btn--tab-menu z-20"
            :style="!tabItems ? 'background-color: #1479FF; color: #fff' : ''"
            @click="tabItems = false"
          >
            1 Месяц
          </Button>
          <Button
            class="btn btn--tab-menu z-20"
            :style="tabItems ? 'background-color: #1479FF; color: #fff' : ''"
            @click="tabItems = true"
          >
            1 Год
          </Button>
        </div>
        <TabView class="mt-4 md:mt-0">
          <TabPanel header="1 кресло">
            <div class="grid">
              <div class="col-12 md:col-5">
                <div v-if="tabItems" class="flex items-center justify-content-between md:justify-content-start gap-8">
                  <p class="tab-menu-price__new-price">
                    100 $
                  </p>
                  <p class="tab-menu-price__old-price">
                    120 $
                  </p>
                </div>
                <div v-else class="flex items-center justify-content-between md:justify-content-start gap-8">
                  <p class="tab-menu-price__new-price">
                    10 $
                  </p>
                  <p class="tab-menu-price__old-price">
                    20 $
                  </p>
                </div>
                <p class="tab-menu-price__description line-height-2">
                  В месяц Denttish предоставляет  возможность эффективного управления
                </p>
                <Button
                  class="btn btn--tab-menu btn--buy"
                  @click="visible = true"
                >
                  Купить
                </Button>
              </div>
              <div class="col-12 md:col-7 order--1 md:order-1 pl-6 md:pl-0">
                <div class="flex flex-column md:flex-row">
                  <ul class="list-menu list-menu--tariff mb-0 md:mb-3">
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Расписание и запись пациентов
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Пациенты
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Услуги
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Персонал
                      </p>
                    </li>
                  </ul>
                  <ul class="list-menu list-menu--tariff mt-0 md:mt-3">
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Отчеты
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Бухгалтерия
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Склад
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Настройки
                      </p>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </TabPanel>
          <TabPanel header="2-4 кресло">
            <div class="grid">
              <div class="col-12 md:col-5">
                <div v-if="tabItems" class="flex items-center justify-content-between md:justify-content-start gap-8">
                  <p class="tab-menu-price__new-price">
                    400 $
                  </p>
                  <p class="tab-menu-price__old-price">
                    440 $
                  </p>
                </div>
                <div v-else class="flex items-center gap-8">
                  <p class="tab-menu-price__new-price">
                    50 $
                  </p>
                  <p class="tab-menu-price__old-price">
                    70 $
                  </p>
                </div>
                <p class="tab-menu-price__description line-height-2">
                  В месяц Denttish предоставляет  возможность эффективного управления
                </p>
                <Button
                  class="btn btn--tab-menu btn--buy"
                  @click="visible = true"
                >
                  Купить
                </Button>
              </div>
              <div class="col-12 md:col-7 order--1 md:order-1 pl-6 md:pl-0">
                <div class="flex flex-column md:flex-row">
                  <ul class="list-menu list-menu--tariff mb-0 md:mb-3">
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Расписание и запись пациентов
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Пациенты
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Услуги
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Персонал
                      </p>
                    </li>
                  </ul>
                  <ul class="list-menu list-menu--tariff mt-0 md:mt-3">
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Отчеты
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Бухгалтерия
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Склад
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Настройки
                      </p>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </TabPanel>
          <TabPanel header="5+ кресло">
            <div class="grid">
              <div class="col-12 md:col-5">
                <div v-if="tabItems" class="flex items-center justify-content-between md:justify-content-start gap-8">
                  <p class="tab-menu-price__new-price">
                    700 $
                  </p>
                  <p class="tab-menu-price__old-price">
                    770 $
                  </p>
                </div>
                <div v-else class="flex items-center gap-8">
                  <p class="tab-menu-price__new-price">
                    70 $
                  </p>
                  <p class="tab-menu-price__old-price">
                    100 $
                  </p>
                </div>
                <p class="tab-menu-price__description line-height-2">
                  В месяц Denttish предоставляет  возможность эффективного управления
                </p>
                <Button
                  class="btn btn--tab-menu btn--buy"
                  @click="visible = true"
                >
                  Купить
                </Button>
              </div>
              <div class="col-12 md:col-7 order--1 md:order-1 pl-6 md:pl-0">
                <div class="flex flex-column md:flex-row">
                  <ul class="list-menu list-menu--tariff mb-0 md:mb-3">
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Расписание и запись пациентов
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Пациенты
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Услуги
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Персонал
                      </p>
                    </li>
                  </ul>
                  <ul class="list-menu list-menu--tariff mt-0 md:mt-3">
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Отчеты
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Бухгалтерия
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Склад
                      </p>
                    </li>
                    <li>
                      <div class="bg-img">
                        <img src="/layout/images/check-icon.svg" alt="">
                      </div>
                      <p class="tab-menu-price__description--service">
                        Настройки
                      </p>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </TabPanel>
        </TabView>

        <Dialog
          v-model:visible="visible"
          modal
          header="Отправить заявку"
          :style="{ width: '50rem' }"
          class="main-dialog"
        >
          <div class="grid mt-2 border-top-1 pt-5">
            <div class="col-12 md:col-6 pl-0">
              <form class="form form--tariff">
                <InputText class="w-full" placeholder="Имя" />
              </form>
            </div>
            <div class="col-12 md:col-6 pr-0">
              <form action="" class="form form--tariff">
                <InputNumber placeholder="Номер телефона" />
              </form>
            </div>
            <div class="col-12 md:col-6 pl-0">
              <form action="" class="form form--tariff">
                <InputText placeholder="Электронная почта" />
              </form>
            </div>
            <div class="col-12 md:col-6 pr-0">
              <form action="" class="form form--tariff">
                <InputText placeholder="Названия клиника" />
              </form>
            </div>
          </div>
          <div class="flex justify-content-end gap-2">
            <Button type="button" label="Отправить" class="btn btn-primary border-round-2xl" @click="visible = false" />
          </div>
        </Dialog>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
const tabItems = ref(false)
const visible = ref(false)
</script>
