<script setup lang="ts">
useHead({
  title: 'Denttish | Тур в системе'
})

const youtube = () => {
  window.open('https://www.youtube.com/watch?v=4')
}
</script>

<template>
  <div>
    <section class="px-4">
      <TabView class="hidden md:flex tour-system mb-6">
        <TabPanel>
          <template #header>
            <div class="flex align-items-center gap-2">
              <i class="pi pi-sign-in text-2xl" />
              <p>Вход систему</p>
            </div>
          </template>
          <div>
            <h2 class="tour-system__caption">
              Вход в систему
            </h2>
            <p class="tour-system__description">
              Откройте веб-браузер и введите URL “denttish.dev”  CRM-системы в адресной строке.
              или можете через сайта есть кнопка верхнем правом углу
            </p>
            <img src="/layout/images/group1.png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Введите ваш логин и пароль в соответствующие поля на странице входа.
              Нажмите кнопку "Вход" или нажмите клавишу Enter.
              При успешном входе вы окажетесь на главной странице CRM-системы, готовые к работе
            </p>
            <img src="/layout/images/group2.png" alt="" class="tour-system__img">
          </div>
        </TabPanel>
        <TabPanel>
          <template #header>
            <div class="flex align-items-center gap-2">
              <svg width="22" height="22" viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M8 17L1 21V5L8 1M8 17L15 21M8 17V1M15 21L21 17V1L15 5M15 21V5M15 5L8 1" stroke="#526477" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
              </svg>
              <p>Обзор интерфейса</p>
            </div>
          </template>
          <div>
            <h2 class="tour-system__caption">
              Пациенты - Карточка пациента
            </h2>
            <p class="tour-system__description">
              Вся информация по пациенту консолидируется в единой карточке.
              Визиты, история лечения, документы, оплаты, депозит и бонусы, снимки, договора и согласия, печать 043 и 058 карточки, актов и многое другое.
            </p>
            <img src="/layout/images/image25.png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Карточка пациента - Зубная формула
            </h2>
            <p class="tour-system__description">
              Зубная формула консолидирует всю информацию из лечений, а также на основании первичного осмотра.
            </p>
            <img src="/layout/images/image25(1).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Карточка пациента - Оплаты
            </h2>
            <p class="tour-system__description">
              Все оплаты пациента - в одном месте. Печать чека или квитанции в один клик.
            </p>
            <img src="/layout/images/image25(2).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Карточка пациента - Планы лечений
            </h2>
            <p class="tour-system__description">
              Составляйте легко и просто - сложные планы лечений, который состоят из этапов, отслеживайте перемещение пациента с одного этапа на другой этап. Применяйте план лечение при создании акта лечения.
            </p>
            <img src="/layout/images/image25(3).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Карточка пациента - Снимки
            </h2>
            <p class="tour-system__description">
              Загружаете снимки до и после, рентен и панорамные снимки в формате JPG, GIF, PNG, а на тяжелые снимки сохраняйте ссылки.
            </p>
            <img src="/layout/images/image25(4).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Персонал
            </h2>
            <p class="tour-system__description">
              Управляйте персоналом, создавайте графики работ, устанавливайте виды начисления зарплат.
            </p>
            <img src="/layout/images/image25(5).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Услуги и прайс-лист
            </h2>
            <p class="tour-system__description">
              Управляйте прайс-листом, закрепляйте материалы, которые будут автоматически списываться со склада при оказании услуги, устанавливайте индивидуальные % и ставки на услуги и категории.
            </p>
            <img src="/layout/images/image25(6).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Предварительный прейскурант
            </h2>
            <p class="tour-system__description">
              На этой странице вы можете выстовить минимальные и максимальные цены на ваши услуги. Это удобно тем что при предворительной консультации вы можете показать поциенту минимальную и максимальную сумму лечения.
            </p>
            <img src="/layout/images/image25(7).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Редактировать
            </h2>
            <p class="tour-system__description">
              Нажав на три точки справа вы войдете в меню редактирования цен
            </p>
            <img src="/layout/images/image25(8).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Обнавить данные
            </h2>
            <p class="tour-system__description">
              На этом меню вы можете написать название услуги его максимальную и минимальную цену. Кнопкой “добавить элемент” вы можете определить котегорию услуги.
            </p>
            <img src="/layout/images/image26.png" alt="" class="tour-system__img">
          </div>
        </TabPanel>
        <TabPanel>
          <template #header>
            <div class="flex align-items-start gap-2">
              <svg width="22" height="22" viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.5295 7.35186C11.9571 7.75995 11.2566 8 10.5 8C8.567 8 7 6.433 7 4.5C7 2.567 8.567 1 10.5 1C11.753 1 12.8522 1.65842 13.4705 2.64814M5 19.0872H7.61029C7.95063 19.0872 8.28888 19.1277 8.61881 19.2086L11.3769 19.8789C11.9753 20.0247 12.5988 20.0388 13.2035 19.9214L16.253 19.3281C17.0585 19.1712 17.7996 18.7854 18.3803 18.2205L20.5379 16.1217C21.154 15.5234 21.154 14.5524 20.5379 13.9531C19.9832 13.4134 19.1047 13.3527 18.4771 13.8103L15.9626 15.6449C15.6025 15.9081 15.1643 16.0498 14.7137 16.0498H12.2855L13.8311 16.0498C14.7022 16.0498 15.4079 15.3633 15.4079 14.5159V14.2091C15.4079 13.5055 14.9156 12.892 14.2141 12.7219L11.8286 12.1417C11.4404 12.0476 11.0428 12 10.6431 12C9.67833 12 7.93189 12.7988 7.93189 12.7988L5 14.0249M19 5.5C19 7.433 17.433 9 15.5 9C13.567 9 12 7.433 12 5.5C12 3.567 13.567 2 15.5 2C17.433 2 19 3.567 19 5.5ZM1 13.6L1 19.4C1 19.9601 1 20.2401 1.10899 20.454C1.20487 20.6422 1.35785 20.7951 1.54601 20.891C1.75992 21 2.03995 21 2.6 21H3.4C3.96005 21 4.24008 21 4.45399 20.891C4.64215 20.7951 4.79513 20.6422 4.89101 20.454C5 20.2401 5 19.9601 5 19.4V13.6C5 13.0399 5 12.7599 4.89101 12.546C4.79513 12.3578 4.64215 12.2049 4.45399 12.109C4.24008 12 3.96005 12 3.4 12L2.6 12C2.03995 12 1.75992 12 1.54601 12.109C1.35785 12.2049 1.20487 12.3578 1.10899 12.546C1 12.7599 1 13.0399 1 13.6Z" stroke="#526477" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" />
              </svg>
              <p>Услуги и цены</p>
            </div>
          </template>
          <div>
            <p class="tour-system__description">
              Для того, чтобы создать услугу (прайс), необходимо перейти в раздел «Услуги». Затем нажимаете кнопку «Добавить»:
            </p>
            <img src="/layout/images/group5.png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Появится всплывающее окно.
            </h2>
            <p class="tour-system__description">
              Заполняете его по образцу на рисунке ниже:
            </p>
            <img src="/layout/images/group6.png" alt="" class="tour-system__img">
          </div>
        </TabPanel>
        <TabPanel>
          <template #header>
            <div class="flex align-items-center gap-2">
              <svg width="22" height="18" viewBox="0 0 22 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M19 6.5V4.2C19 3.0799 19 2.51984 18.782 2.09202C18.5903 1.7157 18.2843 1.40974 17.908 1.21799C17.4802 1 16.9201 1 15.8 1H4.2C3.0799 1 2.51984 1 2.09202 1.21799C1.7157 1.40973 1.40973 1.71569 1.21799 2.09202C1 2.51984 1 3.0799 1 4.2V13.8C1 14.9201 1 15.4802 1.21799 15.908C1.40973 16.2843 1.71569 16.5903 2.09202 16.782C2.51984 17 3.07989 17 4.2 17L15.8 17C16.9201 17 17.4802 17 17.908 16.782C18.2843 16.5903 18.5903 16.2843 18.782 15.908C19 15.4802 19 14.9201 19 13.8V11.5M14 9C14 8.53535 14 8.30302 14.0384 8.10982C14.1962 7.31644 14.8164 6.69624 15.6098 6.53843C15.803 6.5 16.0353 6.5 16.5 6.5H18.5C18.9647 6.5 19.197 6.5 19.3902 6.53843C20.1836 6.69624 20.8038 7.31644 20.9616 8.10982C21 8.30302 21 8.53535 21 9C21 9.46466 21 9.69698 20.9616 9.89018C20.8038 10.6836 20.1836 11.3038 19.3902 11.4616C19.197 11.5 18.9647 11.5 18.5 11.5H16.5C16.0353 11.5 15.803 11.5 15.6098 11.4616C14.8164 11.3038 14.1962 10.6836 14.0384 9.89018C14 9.69698 14 9.46465 14 9Z" stroke="#526477" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
              </svg>
              <p>Оплата услуги</p>
            </div>
          </template>
          <div>
            <p class="tour-system__description">
              После проведения услуги, необходимо провести оплату. Для проведения оплаты в Календаре нужно нажать на запись пациента и затем нажать на кнопку «Принять оплату»:
            </p>
            <img src="/layout/images/group3.png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Выбираете нужную услугу и нажимаете на нее. Затем в поле Оплата заполняете сумму оплаты, далее выбираете форму оплаты (Наличные Безнал, Перевод на карту, Страховка, Депозит) и нажимаете «Произвести оплату»:
            </p>
            <img src="/layout/images/group4.png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              После нажатия кнопки «Произвести оплату» выскочит меню «Оплата указанных услуг». Там можно распечатать квитанцию, счет и акт:
            </p>
          </div>
        </TabPanel>
        <TabPanel>
          <template #header>
            <div class="flex align-items-center gap-2">
              <svg width="22" height="20" viewBox="0 0 22 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M11 13.5H6.5C5.10444 13.5 4.40665 13.5 3.83886 13.6722C2.56045 14.06 1.56004 15.0605 1.17224 16.3389C1 16.9067 1 17.6044 1 19M18 19V13M15 16H21M13.5 5.5C13.5 7.98528 11.4853 10 9 10C6.51472 10 4.5 7.98528 4.5 5.5C4.5 3.01472 6.51472 1 9 1C11.4853 1 13.5 3.01472 13.5 5.5Z" stroke="#526477" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
              </svg>
              <p>Запись поциента</p>
            </div>
          </template>
          <div>
            <p class="tour-system__description">
              Чтобы записать пациента на прием, перейдите в раздел «Календарь». Перед вами появится график работы доктора на сегодняшний день.
            </p>
            <img src="/layout/images/image25(9).png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Затем заполняете карточку (обязательные поля обозначены *). Пример заполнения карточки доктора показано на рисунках ниже:
            </p>
            <img src="/layout/images/image25(10).png" alt="" class="tour-system__img">
            <img src="/layout/images/image25(11).png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Затем заполняете карточку (обязательные поля обозначены *). Пример заполнения карточки доктора показано на рисунках ниже:
            </p>
            <img src="/layout/images/image25(12).png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Затем заполняете карточку (обязательные поля обозначены *). Пример заполнения карточки доктора показано на рисунках ниже:
            </p>
            <img src="/layout/images/image25(13).png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Затем заполняете карточку (обязательные поля обозначены *). Пример заполнения карточки доктора показано на рисунках ниже:
            </p>
          </div>
        </TabPanel>
        <TabPanel>
          <template #header>
            <div class="flex align-items-center gap-2">
              <svg width="19" height="22" viewBox="0 0 19 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M17 11.5V5.8C17 4.11984 17 3.27976 16.673 2.63803C16.3854 2.07354 15.9265 1.6146 15.362 1.32698C14.7202 1 13.8802 1 12.2 1H5.8C4.11984 1 3.27976 1 2.63803 1.32698C2.07354 1.6146 1.6146 2.07354 1.32698 2.63803C1 3.27976 1 4.11984 1 5.8V16.2C1 17.8802 1 18.7202 1.32698 19.362C1.6146 19.9265 2.07354 20.3854 2.63803 20.673C3.27976 21 4.11984 21 5.8 21H9M11 10H5M7 14H5M13 6H5M11.5 18L13.5 20L18 15.5" stroke="#526477" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
              </svg>
              <p>Создание персонала</p>
            </div>
          </template>
          <div>
            <h2 class="tour-system__caption">
              Появится всплывающее окно.
            </h2>
            <p class="tour-system__description">
              Заполняете его по образцу на рисунке ниже:
            </p>
            <img src="/layout/images/group7.png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Затем заполняете карточку (обязательные поля обозначены *). Пример заполнения карточки доктора показано на рисунках ниже:
            </p>
            <img src="/layout/images/group8.png" alt="" class="tour-system__img">
          </div>
        </TabPanel>
        <TabPanel>
          <template #header>
            <div class="flex align-items-center gap-2" @click="youtube">
              <svg width="31" height="22" viewBox="0 0 31 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M15.6364 0.423901C17.6629 0.43522 24.9005 0.514452 26.927 1.06908C28.2212 1.4175 29.2415 2.43788 29.59 3.73201C30.1446 5.75854 30.2056 9.66837 30.2117 10.7441L30.2113 11.205C30.2041 12.1114 30.1411 16.1969 29.59 18.291C29.2415 19.5852 28.2212 20.6055 26.927 20.954C24.6592 21.5507 15.8658 21.5751 15.1517 21.5761H15.0596C14.3474 21.5751 5.57583 21.5497 3.28418 20.9291C1.99004 20.5807 0.969672 19.5603 0.621251 18.2661C0.0701771 16.1941 0.00719802 12.0916 0 11.1809V10.8181C0.00719802 9.9116 0.0701771 5.82609 0.621251 3.73201C0.969672 2.43788 2.01493 1.39261 3.28418 1.04419C5.31071 0.510897 12.5483 0.434712 14.5748 0.423828L15.6364 0.423901ZM12.0943 6.4696V15.5285L19.9586 10.9991L12.0943 6.4696Z" fill="#5D6E7F" />
              </svg>
              <p>Youtube</p>
            </div>
          </template>
        </TabPanel>
      </TabView>
      <Accordion
        :active-index="0"
        expand-icon="pi pi-angle-down"
        collapse-icon="pi pi-angle-up"
        class="tour-system-mobile flex-block md:hidden"
      >
        <AccordionTab>
          <template #header>
            <div class="flex align-items-center gap-2 order--1">
              <i class="pi pi-sign-in text-2xl" />
              <p>Вход систему</p>
            </div>
          </template>
          <div>
            <h2 class="tour-system__caption">
              Вход в систему
            </h2>
            <p class="tour-system__description">
              Откройте веб-браузер и введите URL “denttish.dev”  CRM-системы в адресной строке.
              или можете через сайта есть кнопка верхнем правом углу
            </p>
            <img src="/layout/images/group1.png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Введите ваш логин и пароль в соответствующие поля на странице входа.
              Нажмите кнопку "Вход" или нажмите клавишу Enter.
              При успешном входе вы окажетесь на главной странице CRM-системы, готовые к работе
            </p>
            <img src="/layout/images/group2.png" alt="" class="tour-system__img">
          </div>
        </AccordionTab>
        <AccordionTab>
          <template #header>
            <div class="flex align-items-center gap-2 order--1">
              <svg width="22" height="22" viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M8 17L1 21V5L8 1M8 17L15 21M8 17V1M15 21L21 17V1L15 5M15 21V5M15 5L8 1" stroke="#526477" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
              </svg>
              <p>Обзор интерфейса</p>
            </div>
          </template>
          <div>
            <h2 class="tour-system__caption">
              Пациенты - Карточка пациента
            </h2>
            <p class="tour-system__description">
              Вся информация по пациенту консолидируется в единой карточке.
              Визиты, история лечения, документы, оплаты, депозит и бонусы, снимки, договора и согласия, печать 043 и 058 карточки, актов и многое другое.
            </p>
            <img src="/layout/images/image25.png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Карточка пациента - Зубная формула
            </h2>
            <p class="tour-system__description">
              Зубная формула консолидирует всю информацию из лечений, а также на основании первичного осмотра.
            </p>
            <img src="/layout/images/image25(1).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Карточка пациента - Оплаты
            </h2>
            <p class="tour-system__description">
              Все оплаты пациента - в одном месте. Печать чека или квитанции в один клик.
            </p>
            <img src="/layout/images/image25(2).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Карточка пациента - Планы лечений
            </h2>
            <p class="tour-system__description">
              Составляйте легко и просто - сложные планы лечений, который состоят из этапов, отслеживайте перемещение пациента с одного этапа на другой этап. Применяйте план лечение при создании акта лечения.
            </p>
            <img src="/layout/images/image25(3).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Карточка пациента - Снимки
            </h2>
            <p class="tour-system__description">
              Загружаете снимки до и после, рентен и панорамные снимки в формате JPG, GIF, PNG, а на тяжелые снимки сохраняйте ссылки.
            </p>
            <img src="/layout/images/image25(4).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Персонал
            </h2>
            <p class="tour-system__description">
              Управляйте персоналом, создавайте графики работ, устанавливайте виды начисления зарплат.
            </p>
            <img src="/layout/images/image25(5).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Услуги и прайс-лист
            </h2>
            <p class="tour-system__description">
              Управляйте прайс-листом, закрепляйте материалы, которые будут автоматически списываться со склада при оказании услуги, устанавливайте индивидуальные % и ставки на услуги и категории.
            </p>
            <img src="/layout/images/image25(6).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Предварительный прейскурант
            </h2>
            <p class="tour-system__description">
              На этой странице вы можете выстовить минимальные и максимальные цены на ваши услуги. Это удобно тем что при предворительной консультации вы можете показать поциенту минимальную и максимальную сумму лечения.
            </p>
            <img src="/layout/images/image25(7).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Редактировать
            </h2>
            <p class="tour-system__description">
              Нажав на три точки справа вы войдете в меню редактирования цен
            </p>
            <img src="/layout/images/image25(8).png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Обнавить данные
            </h2>
            <p class="tour-system__description">
              На этом меню вы можете написать название услуги его максимальную и минимальную цену. Кнопкой “добавить элемент” вы можете определить котегорию услуги.
            </p>
            <img src="/layout/images/image26.png" alt="" class="tour-system__img">
          </div>
        </AccordionTab>
        <AccordionTab>
          <template #header>
            <div class="flex align-items-start gap-2 order--1">
              <svg width="22" height="22" viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.5295 7.35186C11.9571 7.75995 11.2566 8 10.5 8C8.567 8 7 6.433 7 4.5C7 2.567 8.567 1 10.5 1C11.753 1 12.8522 1.65842 13.4705 2.64814M5 19.0872H7.61029C7.95063 19.0872 8.28888 19.1277 8.61881 19.2086L11.3769 19.8789C11.9753 20.0247 12.5988 20.0388 13.2035 19.9214L16.253 19.3281C17.0585 19.1712 17.7996 18.7854 18.3803 18.2205L20.5379 16.1217C21.154 15.5234 21.154 14.5524 20.5379 13.9531C19.9832 13.4134 19.1047 13.3527 18.4771 13.8103L15.9626 15.6449C15.6025 15.9081 15.1643 16.0498 14.7137 16.0498H12.2855L13.8311 16.0498C14.7022 16.0498 15.4079 15.3633 15.4079 14.5159V14.2091C15.4079 13.5055 14.9156 12.892 14.2141 12.7219L11.8286 12.1417C11.4404 12.0476 11.0428 12 10.6431 12C9.67833 12 7.93189 12.7988 7.93189 12.7988L5 14.0249M19 5.5C19 7.433 17.433 9 15.5 9C13.567 9 12 7.433 12 5.5C12 3.567 13.567 2 15.5 2C17.433 2 19 3.567 19 5.5ZM1 13.6L1 19.4C1 19.9601 1 20.2401 1.10899 20.454C1.20487 20.6422 1.35785 20.7951 1.54601 20.891C1.75992 21 2.03995 21 2.6 21H3.4C3.96005 21 4.24008 21 4.45399 20.891C4.64215 20.7951 4.79513 20.6422 4.89101 20.454C5 20.2401 5 19.9601 5 19.4V13.6C5 13.0399 5 12.7599 4.89101 12.546C4.79513 12.3578 4.64215 12.2049 4.45399 12.109C4.24008 12 3.96005 12 3.4 12L2.6 12C2.03995 12 1.75992 12 1.54601 12.109C1.35785 12.2049 1.20487 12.3578 1.10899 12.546C1 12.7599 1 13.0399 1 13.6Z" stroke="#526477" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" />
              </svg>
              <p>Услуги и цены</p>
            </div>
          </template>
          <div>
            <p class="tour-system__description">
              Для того, чтобы создать услугу (прайс), необходимо перейти в раздел «Услуги». Затем нажимаете кнопку «Добавить»:
            </p>
            <img src="/layout/images/group5.png" alt="" class="tour-system__img">
            <h2 class="tour-system__caption">
              Появится всплывающее окно.
            </h2>
            <p class="tour-system__description">
              Заполняете его по образцу на рисунке ниже:
            </p>
            <img src="/layout/images/group6.png" alt="" class="tour-system__img">
          </div>
        </AccordionTab>
        <AccordionTab>
          <template #header>
            <div class="flex align-items-center gap-2 order--1">
              <svg width="22" height="18" viewBox="0 0 22 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M19 6.5V4.2C19 3.0799 19 2.51984 18.782 2.09202C18.5903 1.7157 18.2843 1.40974 17.908 1.21799C17.4802 1 16.9201 1 15.8 1H4.2C3.0799 1 2.51984 1 2.09202 1.21799C1.7157 1.40973 1.40973 1.71569 1.21799 2.09202C1 2.51984 1 3.0799 1 4.2V13.8C1 14.9201 1 15.4802 1.21799 15.908C1.40973 16.2843 1.71569 16.5903 2.09202 16.782C2.51984 17 3.07989 17 4.2 17L15.8 17C16.9201 17 17.4802 17 17.908 16.782C18.2843 16.5903 18.5903 16.2843 18.782 15.908C19 15.4802 19 14.9201 19 13.8V11.5M14 9C14 8.53535 14 8.30302 14.0384 8.10982C14.1962 7.31644 14.8164 6.69624 15.6098 6.53843C15.803 6.5 16.0353 6.5 16.5 6.5H18.5C18.9647 6.5 19.197 6.5 19.3902 6.53843C20.1836 6.69624 20.8038 7.31644 20.9616 8.10982C21 8.30302 21 8.53535 21 9C21 9.46466 21 9.69698 20.9616 9.89018C20.8038 10.6836 20.1836 11.3038 19.3902 11.4616C19.197 11.5 18.9647 11.5 18.5 11.5H16.5C16.0353 11.5 15.803 11.5 15.6098 11.4616C14.8164 11.3038 14.1962 10.6836 14.0384 9.89018C14 9.69698 14 9.46465 14 9Z" stroke="#526477" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
              </svg>
              <p>Оплата услуги</p>
            </div>
          </template>
          <div>
            <p class="tour-system__description">
              После проведения услуги, необходимо провести оплату. Для проведения оплаты в Календаре нужно нажать на запись пациента и затем нажать на кнопку «Принять оплату»:
            </p>
            <img src="/layout/images/group3.png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Выбираете нужную услугу и нажимаете на нее. Затем в поле Оплата заполняете сумму оплаты, далее выбираете форму оплаты (Наличные Безнал, Перевод на карту, Страховка, Депозит) и нажимаете «Произвести оплату»:
            </p>
            <img src="/layout/images/group4.png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              После нажатия кнопки «Произвести оплату» выскочит меню «Оплата указанных услуг». Там можно распечатать квитанцию, счет и акт:
            </p>
          </div>
        </AccordionTab>
        <AccordionTab>
          <template #header>
            <div class="flex align-items-center gap-2 order--1">
              <svg width="22" height="20" viewBox="0 0 22 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M11 13.5H6.5C5.10444 13.5 4.40665 13.5 3.83886 13.6722C2.56045 14.06 1.56004 15.0605 1.17224 16.3389C1 16.9067 1 17.6044 1 19M18 19V13M15 16H21M13.5 5.5C13.5 7.98528 11.4853 10 9 10C6.51472 10 4.5 7.98528 4.5 5.5C4.5 3.01472 6.51472 1 9 1C11.4853 1 13.5 3.01472 13.5 5.5Z" stroke="#526477" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
              </svg>
              <p>Запись поциента</p>
            </div>
          </template>
          <div>
            <p class="tour-system__description">
              Чтобы записать пациента на прием, перейдите в раздел «Календарь». Перед вами появится график работы доктора на сегодняшний день.
            </p>
            <img src="/layout/images/image25(9).png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Затем заполняете карточку (обязательные поля обозначены *). Пример заполнения карточки доктора показано на рисунках ниже:
            </p>
            <img src="/layout/images/image25(10).png" alt="" class="tour-system__img">
            <img src="/layout/images/image25(11).png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Затем заполняете карточку (обязательные поля обозначены *). Пример заполнения карточки доктора показано на рисунках ниже:
            </p>
            <img src="/layout/images/image25(12).png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Затем заполняете карточку (обязательные поля обозначены *). Пример заполнения карточки доктора показано на рисунках ниже:
            </p>
            <img src="/layout/images/image25(13).png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Затем заполняете карточку (обязательные поля обозначены *). Пример заполнения карточки доктора показано на рисунках ниже:
            </p>
          </div>
        </AccordionTab>
        <AccordionTab>
          <template #header>
            <div class="flex align-items-center gap-2 order--1">
              <svg width="19" height="22" viewBox="0 0 19 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M17 11.5V5.8C17 4.11984 17 3.27976 16.673 2.63803C16.3854 2.07354 15.9265 1.6146 15.362 1.32698C14.7202 1 13.8802 1 12.2 1H5.8C4.11984 1 3.27976 1 2.63803 1.32698C2.07354 1.6146 1.6146 2.07354 1.32698 2.63803C1 3.27976 1 4.11984 1 5.8V16.2C1 17.8802 1 18.7202 1.32698 19.362C1.6146 19.9265 2.07354 20.3854 2.63803 20.673C3.27976 21 4.11984 21 5.8 21H9M11 10H5M7 14H5M13 6H5M11.5 18L13.5 20L18 15.5" stroke="#526477" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
              </svg>
              <p>Создание персонала</p>
            </div>
          </template>
          <div>
            <h2 class="tour-system__caption">
              Появится всплывающее окно.
            </h2>
            <p class="tour-system__description">
              Заполняете его по образцу на рисунке ниже:
            </p>
            <img src="/layout/images/group7.png" alt="" class="tour-system__img">
            <p class="tour-system__description">
              Затем заполняете карточку (обязательные поля обозначены *). Пример заполнения карточки доктора показано на рисунках ниже:
            </p>
            <img src="/layout/images/group8.png" alt="" class="tour-system__img">
          </div>
        </AccordionTab>
      </Accordion>
      <Accordion
        expand-icon="pi pi-angle-down"
        collapse-icon="pi pi-angle-up"
        class="tour-system-mobile flex-block md:hidden mt-4"
      >
        <AccordionTab>
          <template #header>
            <div class="flex align-items-center gap-2 order--1" @click="youtube">
              <svg width="31" height="22" viewBox="0 0 31 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M15.6364 0.423901C17.6629 0.43522 24.9005 0.514452 26.927 1.06908C28.2212 1.4175 29.2415 2.43788 29.59 3.73201C30.1446 5.75854 30.2056 9.66837 30.2117 10.7441L30.2113 11.205C30.2041 12.1114 30.1411 16.1969 29.59 18.291C29.2415 19.5852 28.2212 20.6055 26.927 20.954C24.6592 21.5507 15.8658 21.5751 15.1517 21.5761H15.0596C14.3474 21.5751 5.57583 21.5497 3.28418 20.9291C1.99004 20.5807 0.969672 19.5603 0.621251 18.2661C0.0701771 16.1941 0.00719802 12.0916 0 11.1809V10.8181C0.00719802 9.9116 0.0701771 5.82609 0.621251 3.73201C0.969672 2.43788 2.01493 1.39261 3.28418 1.04419C5.31071 0.510897 12.5483 0.434712 14.5748 0.423828L15.6364 0.423901ZM12.0943 6.4696V15.5285L19.9586 10.9991L12.0943 6.4696Z" fill="#5D6E7F" />
              </svg>
              <p>Youtube</p>
            </div>
          </template>
          <p class="tour-system__description text-blue-500 mt-2" @click="youtube">
            "Инструкции по использованию CRM можно и посмотреть на YouTube."
          </p>
        </AccordionTab>
      </Accordion>
    </section>
  </div>
</template>
