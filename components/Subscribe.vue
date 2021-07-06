<template>
  <div class="subscribe">
    <div class="container">
      <div class="subscribe_content">
        <div class="subscribe_title">
          ПОДПИСАТЬСЯ НА НОВОСТИ
        </div>
        <div class="subscribe_control">
          <input type="text" class="subscribe_input" placeholder="Ваш e-mail">
          <button class="btn btn_green">Подписаться</button>
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="sass">
.subscribe
  background-color: #404040
  &_content
    display: flex
    align-items: center
    padding: 20px 0
  &_title
    color: #fff
    margin-right: 37px
    font-weight: 700
    align-items: center
    white-space: nowrap
  &_control
    display: flex
    width: 100%
  &_input
    width: 100%
    height: 42px
    border-radius: 3px
    padding-left: 20px
    margin-right: -10px
  .btn
    width: 279px
    flex: 0 0 279px

</style>
