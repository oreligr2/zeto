<template>
  <div class="header_cart">
    <div class="header_cart--content" v-if="!cartItems.length">
      <div class="header_cart--label">
        <span>Корзина</span>
      </div>
      <div class="header_cart--img">
        <img src="../assets/icons/basket.svg" alt="">
      </div>
    </div>
    <div class="header_cart--content" v-if="cartItems.length">
      <div class="header_cart--label">
        <span>Корзина</span>
        <div class="count">
          1 товар - <div class="sum">828 грн</div>
        </div>
      </div>
      <div class="header_cart--img">
        <img src="../assets/icons/basket.svg" alt="">
      </div>
    </div>
    <div class="header_cart--dropdown">
      <div class="cart_dropdown--title">
        <span>(1)</span> Товаров в корзине
      </div>
      <div class="cart_dropdown--items">
        <div class="cart_dropdown--item">
          <div class="cart_dropdown--item_img">
            <img src="../assets/img/img.jpg" alt="">
          </div>
          <div class="cart_dropdown--item_content">
            <div class="cart_dropdown--item_price">
              <span>828</span> грн
            </div>
            <div class="count_input">
              <div class="minus">-</div>
              <input type="number" min="1" value="1">
              <div class="plus">+</div>
            </div>
          </div>
          <div class="cart_dropdown--item_delete">
            <img src="../assets/icons/delete.svg" alt="">
          </div>
        </div>
      </div>
      <div class="cart_dropdown--bottom">
        <div class="cart_dropdown--sum">
          <div class="cart_dropdown--label">Всего:</div>
          <div class="cart_dropdown--price">
            <span>828</span>
            грн
          </div>
        </div>
        <a href="" class="btn btn_green">В корзину</a>
      </div>
    </div>

  </div>
</template>

<style lang="sass">
.header
  &_cart
    margin-left: 20px
    position: relative
    z-index: 3
    &:hover
      .header_cart--dropdown
        display: block
    &--content
      display: flex
      align-items: center
      font-weight: 500
      text-transform: uppercase
    &--img
      height: 40px
      width: 40px
      margin-left: 10px
      display: flex
      align-items: center
      justify-content: center
      background-color: #00B341
      border-radius: 3px
    &--label
      display: flex
      flex-direction: column
      .count
        font-size: 14px
        font-weight: 300
        display: flex
        white-space: nowrap
      .sum
        color: #00B341
        font-weight: 700
        margin-left: 5px
    &--dropdown
      display: none
      position: absolute
      top: 100%
      right: 0
      background-color: #fff
      box-shadow: 0px 0px 20px rgba(0, 179, 65, 0.15), 0px 0px 15px rgba(0, 0, 0, 0.1)
      border-radius: 3px
      color: #000
      width: 326px
      padding-top: 16px

.cart_dropdown
  padding-top: 16px
  &--title
    font-weight: 500
    text-align: center
    font-size: 16px
    text-transform: uppercase
    span
      color: #00B341
  &--items
    padding: 15px 20px 20px
  &--item
    display: flex
    align-items: center
    &_img
      width: 72px
      margin-right: 20px
      box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1)
      border-radius: 3px
      img
        width: 100%
    &_price
      font-size: 16px
      font-weight: 500
      margin-bottom: 10px
      line-height: 24px
      span
        color: #00B341
        font-weight: 700
        font-size: 20px
    &_delete
      width: 30px
      height: 30px
      cursor: pointer
      display: flex
      align-items: center
      justify-content: center
      box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1)
      border-radius: 3px
      margin-left: auto
  &--bottom
    border-top: 1px solid #EFEFEF
    padding: 16px 20px 20px
    .btn
      margin-top: 15px
      width: 100%
  &--sum
    display: flex
    align-items: center
  &--label
    text-transform: uppercase
    font-size: 16px
  &--price
    margin-left: auto
    font-size: 16px
    line-height: 24px
    span
      color: #00B341
      font-size: 20px


.count_input
  width: 99px
  height: 30px
  display: flex
  position: relative
  .plus, .minus
    width: 30px
    height: 30px
    background-color: #fff
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1)
    border-radius: 3px
    position: absolute
    top: 0
    display: flex
    align-items: center
    justify-content: center
    cursor: pointer
  .plus
    right: 0
  .minus
    left: 0
  input
    width: 100%
    text-align: center
    height: 100%
    border: none
    background-color: #EEEFEE
    padding-left: 15px
    font-size: 16px
    font-weight: 500


</style>
<script>

export default {
  data() {
    return {
      cartItems: [
        {
          price: 828
        },
      ]
    }
  },
}
</script>
