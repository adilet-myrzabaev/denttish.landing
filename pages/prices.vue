<template>
  <div>
    <tariff />
    <section class="px-4">
      <div class="grid">
        <div class="col-12 md:col-6">
          <div class="card">
            <ul class="menu-service">
              <li>
                <img src="/layout/icons/add-user-icon.svg" alt="">
                <h4 class="menu-service__caption">
                  Расписание и запись пациентов
                </h4>
                <p class="menu-service__description">
                  В этом разделе Вы можете записывать пациентов на приём, а также отслеживать записи, одним кликом отсюда отправлять уведомление и врачу и пациенту, написать отчет о проделанной работе после приема пациентов и управлять временем ваших врачей.
                </p>
              </li>
              <li>
                <img src="/layout/icons/tv-icon.svg" alt="">
                <h4 class="menu-service__caption">
                  Персонал
                </h4>
                <p class="menu-service__description">
                  В этом разделе Вы можете создавать, редактировать и видеть все данные сотрудников вашей клиники. Также вы можете установить способы выплаты зарплат (т. е. оклад это или проценты) и видеть то сколько заработал сотрудник за определенный период
                </p>
              </li>
              <li>
                <img src="/layout/icons/panel-icon.svg" alt="">
                <h4 class="menu-service__caption">
                  Склад
                </h4>
                <p class="menu-service__description">
                  В этом разделе Вы можете управлять закупками материалов, распределять их по складам, врачам и креслам.
                </p>
              </li>
              <li>
                <img src="/layout/icons/account-icon.svg" alt="">
                <h4 class="menu-service__caption">
                  Отчеты
                </h4>
                <p class="menu-service__description min-h-0">
                  В этом разделе Вы можете сформировать любую отчётность и аналитику за период.
                </p>
              </li>
            </ul>
          </div>
        </div>
        <div class="col-12 md:col-6">
          <div class="card">
            <ul class="menu-service">
              <li>
                <img src="/layout/icons/user-icon.svg" alt="">
                <h4 class="menu-service__caption">
                  Пациенты
                </h4>
                <p class="menu-service__description">
                  В этом разделе ведётся клиентская база и амбулаторные карточки пациентов, с возможностью создавать планы лечений, проводить лечения, заполнение анкеты, видеть всю информацию о визитах и оплатах пациента.
                </p>
              </li>
              <li>
                <img src="/layout/icons/kassa-icon.svg" alt="">
                <h4 class="menu-service__caption">
                  Бухгалтерия
                </h4>
                <p class="menu-service__description">
                  В этом разделе Вы можете следить за всеми финансовыми показателями, контролировать доходы и расходы клинки, выплачивать зарплаты персоналу.
                </p>
              </li>
              <li>
                <img src="/layout/icons/panel-edit-icon.svg" alt="">
                <h4 class="menu-service__caption">
                  Услуги
                </h4>
                <p class="menu-service__description">
                  В этом разделе Вы можете создавать и редактировать прайс-лист.
                </p>
              </li>
              <li>
                <img src="/layout/icons/setting-icon.svg" alt="">
                <h4 class="menu-service__caption">
                  Настройки
                </h4>
                <p class="menu-service__description min-h-0">
                  В этом разделе доступны глобальные настройки для Вашей клиники.
                </p>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
import Tariff from '../components/tariff-menu.vue'

useHead({
  title: 'Denttish | Цена'
})
</script>
<style scoped lang="scss">
.menu-service{
  list-style: none;
  padding: 0 30px;
  & > li {
    margin-bottom: 20px;
    &:last-child {
    margin-bottom: 0;
    }
    & img{
      width: 4rem;
    }
  }
  &__caption{
    color: #092C4C;
    font-size: 28px;
    font-weight: 600;
    line-height: 25px;
    text-align: left;
  }
  &__description{
    color: #092C4C;
    font-size: 20px;
    font-weight: 500;
    line-height: 25px;
    text-align: left;
    min-height: 150px;
  }
}

@media screen and (max-width: 576px) {
  .menu-service{
    padding: 0 10px;
    &__caption{
      font-size: 14px;
      margin: 10px 0;
    }
    &__description{
      font-size: 12px;
      line-height: 20px;
      min-height: 100%;
      margin-bottom: 30px;
    }
    li img{
      width: 3rem;
    }
  }
  .card{
    border-radius: 10px;
  }
}
</style>
