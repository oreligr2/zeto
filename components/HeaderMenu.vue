<template>
<div class="menu">
  <div class="menu_header">
    <div class="menu_close">
      <img src="../assets/icons/cross.svg" alt="">
    </div>
    <div class="menu_logo">
      <img src="../assets/img/logo.svg" alt="">
    </div>
    <div class="header_lang"><div class="header_lang--item">
      RU
    </div> <div class="header_lang--separator">
      |
    </div> <div class="header_lang--item active">
      UA
    </div></div>
  </div>
</div>
</template>

<style lang="sass">
.menu
  position: absolute
  width: 298px
  &_header
    background-color: #323232
    padding: 10px
    display: flex
    .header_lang
      margin-left: auto
  &_logo
    width: 94px
    img
      width: 100%
  &_close
    position: absolute
    top: -23px
    width: 46px
    height: 46px
    background-color: #00B341
    display: flex
    align-items: center
    justify-content: center
    cursor: pointer
    border-radius: 50%
    left: calc(50% - 23px)
</style>
