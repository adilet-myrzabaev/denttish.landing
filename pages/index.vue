<script setup lang='ts'>
</script>

<template>
  <div>
    <section class="banner px-4">
      <div class="grid">
        <div class="col-12 md:col-5">
          <img class="w-full" src="/layout/images/banner.png" alt="banner">
        </div>
        <div class="col-12 md:col-7 pl-7">
          <div class="flex flex-column h-full justify-center">
            <h1 class="caption mb-5">
              Управляйте <br>
              улыбками с легкостью
            </h1>
            <p class="description mb-6">
              Denttish обеспечивает эффективное управление графиком приемов, мгновенную связь с врачами, персонализированное обслуживание и надежное хранение медицинских данных для вашего комфорта и безопасности.
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
    <section class="px-5">
      <div class="grid" style="background-color: #D6E2E0; border-radius: 32px;padding: 78px 80px">
        <div class="col-12 md:col-7">
          <div class="h-full flex flex-column h-full justify-center">
            <h1 class="caption caption--middle mb-4">
              DentTish открывает широкие возможности.
            </h1>
            <p class="description description--middle-gray mb-7">
              DentTish открывает широкие возможности для клиник и медицинских учреждений в области управления и предоставления заботы пациентам. Некоторые из ключевых возможностей включают:
            </p>
            <Button class="btn btn-link btn-link--blue">
              <span class="btn-link__caption">Прочитать</span>
              <div class="bg-link bg-link--blue">
                <img class="bg-link__img" src="/layout/images/Arrow-white.svg" alt="">
              </div>
            </Button>
          </div>
        </div>
        <div class="col-12 md:col-5">
          <div class="grid">
            <div class="col-12 md:col-6 pr-4 pb-4">
              <div class="card">
                <div class="bg-link bg-link--aqua">
                  <img class="bg-link__img" src="/layout/images/check.svg" alt="">
                </div>
                <p class="card__description">
                  Безопасное хранение
                </p>
              </div>
            </div>
            <div class="col-12 md:col-6 pl-4 pb-4">
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
            <div class="col-12 md:col-6 pr-4 pt-4">
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
            <div class="col-12 md:col-6 pl-4 pt-4">
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
    <section class="px-4" style="overflow: hidden">
      <h1 class="caption caption--middle mb-8 mx-auto text-center w-5">
        Кому предназначена
        наш программа?
      </h1>
      <div class="grid">
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
    </section>
    <section class="bg-[#fff]">
      <div class="grid">
        <div class="col-12 md:col-6 pl-8">
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
        <div class="col-12 md:col-6 p-0">
          <div class="bg-out-container">
            <img class="bg-out-container__img" src="/layout/images/demo-version-img.png" alt="">
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="grid">
        <div class="col-12 md:col-7 ">
          <img src="" alt="">
        </div>
        <div class="col-12 md:col-5 ">
          <div>
            <h2 class="caption caption--small mb-3 line-height-2">
              Хотите узнать больше про возможности DentTish для вашей стоматологии?
            </h2>
            <p class="description description--middle description--middle-gray mb-5">
              Оставьте заявку для бесплатной онлайн-презентации
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped></style>
