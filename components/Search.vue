<template>
  <div class="search">
    <div class="search_dropdown">
      <div class="search_dropdown--title">
        <span>Выбрать категорию</span>
        <img src="../assets/icons/arrow-down.svg" alt="">
      </div>
    </div>
    <input type="text" class="search_input" placeholder="Поиск товара">
    <div class="search_btn">
      <img src="../assets/icons/search.svg" alt="">
    </div>
  </div>
</template>


<style lang="sass">
.search
  display: flex
  position: relative
  width: 100%
  &_dropdown
    position: relative
    z-index: 1
    &--title
      background-color: #00B341
      width: 192px
      height: 40px
      border-radius: 3px
      display: flex
      align-items: center
      justify-content: center
      text-transform: uppercase
      font-weight: 500
      cursor: pointer
      img
        margin-left: 11px
  &_input
    width: 100%
    outline: none
    padding-left: 20px
    margin-left: -10px
  &_btn
    position: absolute
    background-color: #00B341
    border-radius: 3px
    display: flex
    align-items: center
    justify-content: center
    top: 0
    right: 0
    width: 40px
    height: 40px
    cursor: pointer

</style>
