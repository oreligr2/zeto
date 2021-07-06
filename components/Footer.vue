<template>
  <div class="footer">
    <div class="footer_content">
      <div class="container">
        <div class="row">
          <div class="col-3">
            <div class="footer_title">
              ИНФОРМАЦИЯ
            </div>
            <ul class="footer_nav">
              <li class="footer_nav--item">
                <a href="" class="footer_nav--link">О нас</a>
              </li>
              <li class="footer_nav--item">
                <a href="" class="footer_nav--link">Сертификаты</a>
              </li>
              <li class="footer_nav--item">
                <a href="" class="footer_nav--link">Продавать на Zeto.ua</a>
              </li>
              <li class="footer_nav--item">
                <a href="" class="footer_nav--link">Пользовательское соглашение</a>
              </li>
              <li class="footer_nav--item">
                <a href="" class="footer_nav--link">Карта сайта</a>
              </li>
            </ul>
          </div>
          <div class="col-5">
            <div class="footer_title">
              ГДЕ КУПИТЬ
            </div>
            <div class="footer_about">
              <div class="footer_about--item">
                <div class="green">г. Киев, ул.Большая Васильковская 143/2</div>
                <span>Пн - Пт: 9:00 - 18:00, Сб: 9:00 - 17:00</span>
                <span>Вс - можете заказать в on-line режиме.</span>
              </div>
              <div class="footer_about--item">
                <div class="green">г. Одесса, ул.Среднефонтанская 19г, ТЦ "Кристалл" этаж 1, магазин №27</div>
                <span>Пн - Пт: 9:00 - 18:00, Сб: 9:00 - 17:00</span>
                <span>Вс - прием заказов в on-line режиме.</span>
              </div>
              <div class="footer_about--item">
                <div class="green">
                  <a href="" class="href">(097) <strong>703-08-08</strong></a>
                  <a href="" class="href">(063) <strong>709-08-08</strong></a>
                  <a href="" class="href">(050) <strong>709-08-08</strong></a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-4">
            <div class="footer_title">Мы в соц. сетях</div>
            <div class="footer_social">
              <a href="" class="footer_social--item">
                <img src="../assets/icons/fb.svg" alt="">
              </a>
              <a href="" class="footer_social--item">
                <img src="../assets/icons/vk.svg" alt="">
              </a>
              <a href="" class="footer_social--item">
                <img src="../assets/icons/yt.svg" alt="">
              </a>
            </div>
            <div class="footer_rec">
              <div class="footer_title">
                РЕКВИЗИТЫ КОМПАНИИ:
              </div>
              <div class="footer_rec--content">
                <p>ИНН: 3111504193</p>
                <p>МФО: 305299</p>
                <p>Р/С: UA063052990000026008006705434</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <Subscribe />
    <copy class="copy">
      Интернет-магазин ZETO © 2008-2021
    </copy>
  </div>
</template>
<style lang="sass">
.footer
  padding: 0
  margin-top: 50px
  &_content
    background-color: #EFEFEF
    padding: 27px 0
  &_title
    font-weight: 700
    text-transform: uppercase
  &_nav
    margin-top: 10px
    &--item
      &:not(:last-child)
        margin-bottom: 10px
    &--link
      color: #000
      font-weight: 400
  &_about
    &--item
      position: relative
      padding-left: 30px
      display: flex
      flex-direction: column
      margin-top: 10px
      font-weight: 400
      padding-right: 90px
      &::before
        content: ''
        height: 100%
        width: 2px
        background-color: #E8712D
        position: absolute
        left: 0
        top: 0
      .green, .href
        color: #00B341
      .href
        &:not(:last-child)
          margin-right: 15px
  &_social
    display: flex
    margin-top: 15px
    align-items: center
    &--item
      &:not(:last-child)
        margin-right: 30px
  &_rec
    margin-top: 25px
    &--content
      font-weight: 400
      margin-top: 10px
      p
        &:not(:last-child)
          margin-bottom: 10px

.copy
  background-color: #323232
  color: #fff
  font-weight: 400
  width: 100%
  display: block
  padding: 13px 0
  text-align: center


</style>
