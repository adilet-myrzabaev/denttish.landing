<template>
  <div class="overflow-hidden">
    <!--  banner  -->
    <section class="banner px-4">
      <div class="grid">
        <div class="col-12 md:col-5">
          <img class="w-full" src="/layout/images/banner.png" alt="banner">
        </div>
        <div class="col-12 md:col-7 md:pl-7">
          <div class="flex flex-column h-full justify-center">
            <h1 class="caption mb-5">
              Управляйте <br>
              улыбками с легкостью
            </h1>
            <p class="description description--mobile mb-6">
              <span>Denttish</span> обеспечивает эффективное управление графиком приемов, мгновенную связь с врачами, персонализированное обслуживание и надежное хранение медицинских данных для вашего комфорта и безопасности.
            </p>
            <Button class="btn btn-link">
              <span class="btn-link__caption">Попробовать демо версию</span>
              <div class="bg-link bg-link--aqua">
                <img class="bg-link__img" src="/layout/images/Arrow-black.svg" alt="">
              </div>
            </Button>
          </div>
        </div>
      </div>
    </section>
    <!--  potential our program  -->
    <section class="sm:px-5">
      <div class="grid border-round-4xl px-3 py-6" style="background-color: #D6E2E0; padding: 78px 80px">
        <div class="col-12 md:col-7">
          <div class="h-full flex flex-column h-full justify-center">
            <h1 class="caption caption--middle mb-4">
              DentTish открывает широкие возможности.
            </h1>
            <p class="description description--middle-gray mb-7">
              DentTish открывает широкие возможности для клиник и медицинских учреждений в области управления и предоставления заботы пациентам. Некоторые из ключевых возможностей включают:
            </p>
            <Button class="btn btn-link btn-link--blue">
              <span class="btn-link__caption"><span class="hidden md:flex">Прочитать</span><span class="flex md:hidden">Дочитать</span></span>
              <div class="bg-link bg-link--blue">
                <img class="bg-link__img" src="/layout/images/Arrow-white.svg" alt="">
              </div>
            </Button>
          </div>
        </div>
        <div class="col-12 md:col-5">
          <div class="grid">
            <div class="col-6 pr-3 md:pr-4 pb-3 md:pb-4">
              <div class="card">
                <div class="bg-link bg-link--aqua">
                  <img class="bg-link__img" src="/layout/images/check.svg" alt="">
                </div>
                <p class="card__description">
                  Безопасное хранение
                </p>
              </div>
            </div>
            <div class="col-6 pl-3 md:pl-4 pb-3 md:pb-4">
              <div class="card">
                <div class="bg-link bg-link--aqua">
                  <img class="bg-link__img" src="/layout/images/msg.svg" alt="">
                </div>
                <p class="card__description">
                  Мгновенная связь
                  с врачами и пациентами
                </p>
              </div>
            </div>
            <div class="col-6 pr-3 md:pr-4 pt-3 md:pt-4">
              <div class="card">
                <div class="bg-link bg-link--aqua">
                  <img class="bg-link__img" src="/layout/images/setka.svg" alt="">
                </div>
                <p class="card__description">
                  Эффективное управление
                  расписанием
                </p>
              </div>
            </div>
            <div class="col-6 pl-3 md:pl-4 pt-3 md:pt-4">
              <div class="card">
                <div class="bg-link bg-link--aqua">
                  <img class="bg-link__img" src="/layout/images/calculator.svg" alt="">
                </div>
                <p class="card__description">
                  Аналитика и отчетность
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!--  our program  -->
    <section class="px-4" style="overflow: hidden">
      <h1 class="caption caption--middle mb-8 mx-auto md:text-center md:w-5">
        Кому предназначена
        наш программа?
      </h1>
      <div class="hidden md:flex grid ">
        <div class="col-12 md:col-6 pr-8">
          <Accordion class="our-program" :active-index="0">
            <AccordionTab header="Владельцам">
              <p class="m-0">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est
                laborum.
              </p>
            </AccordionTab>
            <AccordionTab header="Врачам">
              <p class="m-0">
                Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo
                enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Consectetur, adipisci velit, sed quia non numquam eius modi.
              </p>
            </AccordionTab>
            <AccordionTab header="Администраторам">
              <p class="m-0">
                At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in
                culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus.
              </p>
            </AccordionTab>
          </Accordion>
        </div>
        <div class="col-12 md:col-6 pr-6">
          <div class="grid m-0 p-0">
            <div class="col-12 md:col-4 p-0">
              <div class="col-12 p-0 pb-1">
                <img class="w-full h-full" src="/layout/images/our-pr-img2.png" alt="">
              </div>
              <div class="col-12 p-0 m-0 pb-1">
                <img class="w-full h-full" src="/layout/images/our-pr-img3.png" alt="">
              </div>
            </div>
            <div class="col-12 md:col-8 p-0 pl-2">
              <img class="w-full" src="/layout/images/our-pr-img.png" alt="">
            </div>
          </div>
        </div>
      </div>
      <div class="flex md:hidden our-program-tab ">
        <TabView>
          <TabPanel header="Владельцам">
            <p>DentTish - ключ к процветанию владельца клиники. Этот интегрированный инструмент обеспечивает не только увеличение прибыльности и оптимизацию операционных процессов, но также повышает качество обслуживания пациентов, соблюдает стандарты конфиденциальности и поддерживает рост бизнеса через привлечение новых клиентов и удержание существующих. Владельцу DentTish предоставляет уникальную возможность успешного развития своей клиники в динамичной сфере здравоохранения. <span class="text-blue-500 cursor-pointer">еще...</span></p>
          </TabPanel>
          <TabPanel header="Врачам">
            <p>lorem</p>
          </TabPanel>
          <TabPanel header="Администраторам">
            <p>Lorem.</p>
          </TabPanel>
        </TabView>
      </div>
    </section>
    <!--  demo version  -->
    <section class="md:bg-[#fff]">
      <div class="grid">
        <div class="col-12 md:col-6 px-4 md:pl-8">
          <div class="h-full flex flex-column justify-center">
            <h2 class="caption caption--small mb-3">
              Пробная версия
            </h2>
            <p class="description description--middle mb-5">
              Да, у нас есть демо-версия DentTish, где вы можете ознакомиться с основными функциями системы, включая управление расписанием, взаимодействие с пациентами и аналитику данных. Для доступа и подробностей свяжитесь с нашей службой поддержки.
            </p>
            <Button class="btn btn-link btn-link--blue">
              <span class="btn-link__caption">Узнать больше</span>
              <div class="bg-link bg-link--blue">
                <img class="bg-link__img" src="/layout/images/Arrow-white.svg" alt="">
              </div>
            </Button>
          </div>
        </div>
        <div class="col-12 md:col-6 p-0 order--1 md:order-1">
          <div class="bg-out-container">
            <img class="bg-out-container__img" src="/layout/images/demo-version-img.png" alt="">
          </div>
        </div>
      </div>
    </section>
    <!--  more about us  -->
    <more-about-us new-class="hidden md:flex" />
    <!--  tariff  -->
    <tariff />
    <!--  reviews  -->
    <section class="px-4">
      <div class="flex items-center justify-between mb-6">
        <h2 class="caption caption--middle">
          Что говорят наши клиенты
        </h2>
        <nuxt-link class="hidden sm:flex items-end mr-2.5 text-black font-bold text-sm white-space-nowrap md:text-2xl" to="/reviews">
          Все отзывы
          <span class="ml-1">&gt;</span>
        </nuxt-link>
      </div>
      <TabView class="tabview-custom">
        <TabPanel>
          <template #header>
            <div class="flex align-items-center gap-2">
              <Avatar image="/layout/images/avatar1.png" shape="circle" />
              <div>
                <span class="tabview-custom__name">Доктор Шергазы</span>
                <p class="tabview-custom__prof">
                  Стоматолог
                </p>
              </div>
            </div>
          </template>
          <div>
            <h4 class="tabview-custom__caption">
              “CRM система помагла”
            </h4>
            <div class="star-group">
              <span class="star" />
              <span class="star" />
              <span class="star" />
              <span class="star" />
              <span class="star" />
            </div>
            <p class="tabview-custom__description">
              "CRM система помогла нашей стоматологической клинике стать более организованной. Теперь мы легко записываем пациентов, следим за расписанием и лучше взаимодействуем с ними. Программа делает работу проще, и я доволен её использованием!"
            </p>
          </div>
        </TabPanel>
        <TabPanel>
          <template #header>
            <div class="flex align-items-center gap-2">
              <Avatar image="/layout/images/avatar3.png" shape="circle" />
              <div>
                <span class="tabview-custom__name">Доктор Болот</span>
                <p class="tabview-custom__prof">
                  Стоматолог
                </p>
              </div>
            </div>
          </template>
          <div>
            <h4 class="tabview-custom__caption">
              “Система “Denttish”
            </h4>
            <div class="star-group">
              <span class="star" />
              <span class="star" />
              <span class="star" />
              <span class="star" />
              <span class="star" />
            </div>
            <p class="tabview-custom__description">
              "Система "Denttish" для стоматологических клиник просто супер!  Она помогает нам легко записывать пациентов, вести их медицинские карты и даже управлять финансами. Удобный интерфейс делает  работу очень простой. Эта программа стала нашим помощником, и я всем своим коллегам стоматологам советую использовать "Denttish" - уверен, они оценят, как легко с ней работать. Мы больше не тратим массу времени на рутинные задачи, такие как учет пациентов или составление отчетности. Система автоматизирует эти процессы, освобождая нам время для более важных аспектов работы с пациентами."
            </p>
          </div>
        </TabPanel>
        <TabPanel>
          <template #header>
            <div class="flex align-items-center gap-2">
              <Avatar image="/layout/images/avatar2.png" shape="circle" />
              <div>
                <span class="tabview-custom__name">Доктор Чынгыз</span>
                <p class="tabview-custom__prof">
                  Стоматолог
                </p>
              </div>
            </div>
          </template>
          <div>
            <h4 class="tabview-custom__caption">
              “Ыраазычылык билдирем”
            </h4>
            <div class="star-group">
              <span class="star" />
              <span class="star" />
              <span class="star" />
              <span class="star" />
              <span class="star" />
            </div>
            <p class="tabview-custom__description">
              Бул сайтты ишке ашыргандарга ыраазылык билдирем. Аябай жакшы программа болуптур. Стоматологдордун кыйналып кылган иштерин жеңилдетет экен. Excel деген нерседен кутулуп жакшы болбодубу. Каалаган форматта отчётторду көчүрүп алсаң болот экен, пациенттерге кабар таратуу бизде аябай кыйын иш эле, бул жакта бир бассаң эле болуп калат экен, тушунуктуу, кыскача, ыңгайлуу, аябай сонун болуптур. Башка клиникаларга сунуштайт элем.16:32
            </p>
          </div>
        </TabPanel>
      </TabView>
      <div class="flex align-items-center justify-center mt-3">
        <nuxt-link class="mx-auto text-black font-bold text-sm white-space-nowrap md:text-2xl" to="/reviews">
          Все отзывы
          <span class="ml-1">&gt;</span>
        </nuxt-link>
      </div>
    </section>
    <!--  clinics use our program -->
    <section class="px-4">
      <h2 class="caption caption--middle w-8 line-height-2 text-center mx-auto mb-6">
        Стоматологии, которые используют систему DentTish
      </h2>
      <div class="grid justify-center gap-y-2">
        <div class="col-6 md:col-3">
          <div class="card card--clinic">
            <img src="/layout/images/smaildentclinic.svg" alt="">
          </div>
        </div>
        <div class="col-6 md:col-3">
          <div class="card card--clinic">
            <img src="/layout/images/aziadentclinic.svg" alt="">
          </div>
        </div>
        <div class="col-6 md:col-3">
          <div class="card card--clinic">
            <h4 class="card--clinic__caption">
              Эсте лайт
            </h4>
            <img src="/layout/images/icon-clinics.svg" alt="">
          </div>
        </div>
        <div class="col-6 md:col-3">
          <div class="card card--clinic">
            <h4 class="card--clinic__caption">
              Даминов
            </h4>
            <img src="/layout/images/icon-clinics.svg" alt="">
          </div>
        </div>
        <div class="col-6 md:col-3">
          <div class="card card--clinic">
            <h4 class="card--clinic__caption">
              Умай
            </h4>
            <img src="/layout/images/icon-clinics.svg" alt="">
          </div>
        </div>
        <div class="col-6 md:col-3">
          <div class="card card--clinic">
            <h4 class="card--clinic__caption">
              Сапат
            </h4>
            <img src="/layout/images/icon-clinics.svg" alt="">
          </div>
        </div>
        <div class="col-6 md:col-4">
          <div class="card card--clinic">
            <h4 class="card--clinic__caption">
              Доктор Муслим
            </h4>
            <img src="/layout/images/icon-clinics.svg" alt="">
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<script setup lang="ts">
import Tariff from '../components/tariff-menu.vue'
import MoreAboutUs from '../components/more-about-us.vue'
</script>
<style scoped></style>
