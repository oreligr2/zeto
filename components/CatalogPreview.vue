<template>
  <div class="catalog_preview" v-bind:class="{
    catalog_preview__new: isNew,
    catalog_preview__hit: isHit,
    }">
    <div class="catalog_preview--img">
      <img src="../assets/img/catalog-preview.jpg" alt="">
    </div>
    <div class="catalog_preview--title">
      Матрица Lenovo IDEAPAD 100-15IBD
    </div>
    <div class="catalog_preview--bottom">
      <div class="catalog_preview--prices">
        <div class="price__old">
          2 384 грн
        </div>
        <div class="price">
          <span>2 167</span> грн
        </div>
      </div>
      <div class="catalog_preview--btn">
        <a href="" class="btn btn_green btn_cart">
          <img src="../assets/icons/basket.svg" alt="">
        </a>
      </div>
    </div>
  </div>
</template>
<style lang="sass">
.catalog_preview
  box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1)
  border-radius: 3px
  padding: 10px
  position: relative
  &--img
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1)
    border-radius: 3px
    text-align: center
    img
      max-width: 100%
  &--title
    margin: 15px 10px 0
  &--bottom
    margin-top: 12px
    display: flex
    align-items: center
    justify-content: space-between
    padding: 0 10px
    .btn
      width: 40px
      height: 40px
    .price
      font-size: 20px
      font-weight: 700
      line-height: 24px
      span
        color: #00B341
      &__old
        font-weight: 300
        line-height: 20px
        text-decoration: line-through
  &__new, &__hit
    &::before
      position: absolute
      top: 20px
      left: 0
      width: 80px
      height: 30px
      padding-left: 18px
      text-transform: uppercase
      display: flex
      align-items: center
      color: #fff
  &__new
    &::before
      content: 'New'
      background-color: #00B341
  &__hit
    &::before
      content: 'Hit'
      background-color: #E8712D

</style>
<script>
export default {
  props: ['isNew', 'isHit'],
  data() {
    return {

    }
  }
}
</script>
