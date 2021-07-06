<template>
  <div class="header">
    <div class="header_top">
      <div class="container header_top--content">
        <div class="header_top--links">
          <a href="" class="header_top--link">
            <img src="../assets/icons/delivery.svg" alt="">
            <span>Доставка</span>
          </a>
          <a href="" class="header_top--link">
            <img src="../assets/icons/oplata.svg" alt="">
            <span>Оплата</span>
          </a>
          <a href="" class="header_top--link">
            <img src="../assets/icons/garant.svg" alt="">
            <span>Гарантия</span>
          </a>
          <a href="" class="header_top--link">
            <img src="../assets/icons/sale.svg" alt="">
            <span>Статьи и Акции</span>
          </a>
          <a href="" class="header_top--link">
            <img src="../assets/icons/service.svg" alt="">
            <span>Отзывы</span>
          </a>
          <a href="" class="header_top--link">
            <img src="../assets/icons/review.svg" alt="">
            <span>Сервисный центр</span>
          </a>
          <a href="" class="header_top--link">
            <img src="../assets/icons/service.svg" alt="">
            <span>Вакансии</span>
          </a>
          <a href="" class="header_top--link">
            <img src="../assets/icons/vacancies.svg" alt="">
            <span>Контакты</span>
          </a>
        </div>
        <a href="" class="btn btn_orange btn_lk">
          <img src="../assets/icons/person.svg" alt="">
          <span>Личный кабинет</span>
        </a>
      </div>
    </div>
    <div class="header_main">
      <div class="container header_main--content">
        <div class="header_logo">
          <img src="../assets/img/logo.svg" alt="">
        </div>
        <Search />
        <HeaderCart />
      </div>
    </div>
    <div class="header_bottom">
      <div class="container header_bottom--content">
<!--        <HeaderMenu />-->
        <a href="" class="btn btn_orange btn_lk">
          <img src="../assets/icons/menu.svg" alt="">
          <span>Каталог товаров</span>
        </a>
        <div class="header_numbers">
          <a href="" class="header_number">
            (044) <strong>223-32-39</strong>
          </a>
          <div class="header_numbers--separator"></div>
          <a href="" class="header_number">
            (050) <strong>709-08-08</strong>
          </a>
          <div class="header_numbers--separator"></div>
          <a href="" class="header_number">
            (097) <strong>703-08-08</strong>
          </a>
          <div class="header_numbers--separator"></div>
          <a href="" class="header_number">
            (063) <strong>709-08-08</strong>
          </a>
        </div>
        <div class="header_lang">
          <div class="header_lang--item">
            RU
          </div>
          <div class="header_lang--separator">
            |
          </div>
          <div class="header_lang--item active">
            UA
          </div>
        </div>
        <div class="header_bottom--tooltips">
          <div class="tooltipz">
            <div class="tooltipz_link">
              Условия возврата
            </div>
            <div class="tooltipz_dropdown">
              <div class="tooltipz_dropdown--title">
                Как работают условия возврата
              </div>
              <div class="tooltipz_dropdown--wrap">
                <div class="tooltipz_dropdown--content">
                  <img src="../assets/img/hands-exchanging-cardboard-box.jpg" alt="">
                  <p>
                    Отсутствие у потребителя товарного чека или кассового чека либо иного подтверждающего оплату товара документа не лишает его возможности ссылаться на свидетельские показания.
                  </p>
                  <p>
                    Перечень непродовольственных товаров надлежащего качества, не подлежащих возврату или обмену на аналогичный товар  утверждается Правительством РФ.
                  </p>
                </div>

                <div class="tooltipz_list tooltipz_list__num">
                  <div class="tooltipz_list--item">
                    <div class="tooltipz_list--num">
                      01
                    </div>
                    <div class="tooltipz_list--title">
                      <strong>ОБМЕН/ВОЗВРАТ</strong>
                      <span>В течении 14 дней с момента покупки</span>
                    </div>
                  </div>
                  <div class="tooltipz_list--item">
                    <div class="tooltipz_list--num">
                      02
                    </div>
                    <div class="tooltipz_list--title">
                      <strong>ОБМЕН/ВОЗВРАТ</strong>
                      <span>В течении 14 дней с момента покупки</span>
                    </div>
                  </div>
                  <div class="tooltipz_list--item">
                    <div class="tooltipz_list--num">
                      03
                    </div>
                    <div class="tooltipz_list--title">
                      <strong>ОБМЕН/ВОЗВРАТ</strong>
                      <span>В течении 14 дней с момента покупки</span>
                    </div>
                  </div>
                </div>

              </div>


              <div class="more"><a href="" class="btn btn_more">Больше категорий</a></div>
            </div>
          </div>
          <div class="separator"></div>
          <div class="tooltipz">
            <div class="tooltipz_link">
              Безопасная сделка
            </div>
            <div class="tooltipz_dropdown">
              <div class="tooltipz_dropdown--title">
                Как работает безопасная сделка
              </div>
              <div class="tooltipz_dropdown--wrap">
                <div class="tooltipz_dropdown--content">
                  <img src="../assets/img/hands-exchanging-cardboard-box.jpg" alt="">
                  <p>
                    Отсутствие у потребителя товарного чека или кассового чека либо иного подтверждающего оплату товара документа не лишает его возможности ссылаться на свидетельские показания.
                  </p>
                  <p>
                    Перечень непродовольственных товаров надлежащего качества, не подлежащих возврату или обмену на аналогичный товар  утверждается Правительством РФ.
                  </p>
                </div>

                <div class="tooltipz_list">
                  <div class="tooltipz_list--item">
                    <div class="tooltipz_list--num">
                      01
                    </div>
                    <div class="tooltipz_list--icon">
                      <img src="../assets/icons/list-1.svg" alt="">
                    </div>
                    <div class="tooltipz_list--title">
                      Покупатель делает заказ
                    </div>
                  </div>
                  <div class="tooltipz_list--item">
                    <div class="tooltipz_list--num">
                      02
                    </div>
                    <div class="tooltipz_list--icon">
                      <img src="../assets/icons/list-2.svg" alt="">
                    </div>
                    <div class="tooltipz_list--title">
                      На счету продавца фиксируется сумма равная стоимости заказанного товара
                    </div>
                  </div>
                  <div class="tooltipz_list--item">
                    <div class="tooltipz_list--num">
                      03
                    </div>
                    <div class="tooltipz_list--icon">
                      <img src="../assets/icons/list-3.svg" alt="">
                    </div>
                    <div class="tooltipz_list--title">
                      Продавец отправляет заказ
                    </div>
                  </div>
                  <div class="tooltipz_list--item">
                    <div class="tooltipz_list--num">
                      04
                    </div>
                    <div class="tooltipz_list--icon">
                      <img src="../assets/icons/list-4.svg" alt="">
                    </div>
                    <div class="tooltipz_list--title">
                      Получатель получает заказа
                    </div>
                  </div>
                  <div class="tooltipz_list--item">
                    <div class="tooltipz_list--num">
                      05
                    </div>
                    <div class="tooltipz_list--icon">
                      <img src="../assets/icons/list-5.svg" alt="">
                    </div>
                    <div class="tooltipz_list--title">
                      Деньги на счету продавца разблокированы
                    </div>
                  </div>
                </div>
              </div>

              <div class="more"><a href="" class="btn btn_more">Больше категорий</a></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="sass">
.header
  background-color: #000000
  padding-top: 42px
  color: #fff
  font-size: 14px
  font-weight: 500
  &_top
    background-color: #404040
    &--links
      width: 100%
      display: flex
      justify-content: space-between
      margin-right: 34px
    &--link
      font-size: 14px
      color: #fff
      font-weight: 500
      &:hover
        color: #fff
      img
        margin-right: 9px
    &--content
      display: flex
      align-items: center

  &_main
    background-color: #323232
    padding-top: 20px
    padding-bottom: 20px
    &--content
      display: flex
      justify-content: space-between
      align-items: center


  &_logo
    margin-right: 65px

  &_bottom
    background-color: #404040
    &--content
      display: flex
      align-items: center
    &--tooltips
      height: 42px
      display: flex
      align-items: center
      margin-left: auto
      .separator
        height: 26px
        width: 2px
        background-color: #757575

  &_numbers
    display: flex
    margin-left: 30px
    align-items: center
    &--separator
      width: 4px
      height: 4px
      border-radius: 50%
      background-color: #00B341
      margin-left: 10px
      margin-right: 10px
  &_number
    color: #fff
    font-weight: 300
    strong
      font-weight: 700
    &:hover
      color: #fff

  &_lang
    display: flex
    margin-left: 74px
    &--item
      cursor: pointer
      &.active
        color: #00B341
    &--separator
      margin: 0 10px

.tooltipz
  height: 100%
  position: relative
  &:hover
    .tooltipz_dropdown
      display: block
  &_link
    cursor: pointer
    height: 100%
    color: #fff
    text-transform: uppercase
    display: flex
    align-items: center
    justify-content: center
    padding: 0 20px
    transition: 0.3s
    &:hover
      text-decoration: none
      color: #fff
      background-color: #E8712D
  &_dropdown
    display: none
    position: absolute
    background-color: #fff
    z-index: 3
    top: 100%
    right: 0
    width: 757px
    color: #000
    padding-top: 16px
    padding-left: 30px
    padding-bottom: 20px
    box-shadow: 0px 0px 20px rgba(232, 113, 45, 0.2), 0px 0px 15px rgba(0, 0, 0, 0.1)
    border-radius: 3px
    .more
      width: 100%
    &--title
      width: 100%
      line-height: 20px
      font-size: 20px
      text-align: center
      text-transform: uppercase
    &--content
      width: 55%
      flex: 0 0 55%
      font-size: 14px
      font-weight: 300
      padding-right: 30px
      img, p
        margin-bottom: 15px

    &--list
      width: 45%
    &--wrap
      display: flex
      margin-top: 17px
      margin-bottom: 22px

  &_list
    &--item
      display: flex
      align-items: center
      padding: 10px 20px
      padding-right: 10px
      border-bottom: 1px solid #EFEFEF
    &--num
      font-size: 30px
      line-height: 20px
      color: #EFEFEF

    &--icon
      margin-left: -10px
      width: 35px
      flex: 0 0 35px
      img
        width: 100%

    &--title
      font-size: 14px
      font-weight: 500
      margin-left: 20px
    &__num
      .tooltipz_list
        &--num
          width: 44px
          flex: 0 0 44px
          height: 44px
          background-color: #EFEFEF
          border-radius: 50%
          color: #00B341
          display: flex
          align-items: center
          justify-content: center
        &--title
          strong
            display: block
            font-size: 16px
          span
            font-size: 14px
            font-weight: 300
</style>
<script>
import HeaderMenu from "./HeaderMenu";
export default {
  components: {HeaderMenu}
}
</script>
