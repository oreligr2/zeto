<template>
  <div class="search-components block_dark block_dotes">
    <div class="container">
      <h2 class="h2 h2__light text-center">Поиск запчастей</h2>
      <div class="search-components_row">
        <div class="search-components_item">
          <div class="label">
            Введите категорию
          </div>
          <v-select :options="options"></v-select>
        </div>
        <div class="search-components_item">
          <div class="label">
            Введите подкатегорию
          </div>
          <v-select :options="options"></v-select>
        </div>
        <div class="search-components_item">
          <div class="label">
            Введите бренд
          </div>
          <v-select :options="options"></v-select>
        </div>
        <div class="search-components_item">
          <div class="label">
            Введите серию
          </div>
          <v-select :options="options"></v-select>
        </div>
        <div class="search-components_item">
          <div class="label">
            Введите подсерию
          </div>
          <v-select :options="options"></v-select>
        </div>
        <div class="search-components_item">
          <div class="label">
            Введите модель
          </div>
          <v-select :options="options"></v-select>
        </div>
        <div class="search-components_item">
          <a href="" class="btn btn_green">Найти</a>
        </div>
      </div>
    </div>
    <a href="" class="arrow-more">
      <div class="arrow-more_text">
        Результат
      </div>
      <div class="arrow-more_img">
        <img src="../assets/icons/arrow-down.svg" alt="">
      </div>
    </a>
  </div>
</template>

<style lang="sass">
.search-components
  &_row
    margin-top: 18px
    display: flex
    align-items: flex-end
    margin-right: -14px
    margin-left: -14px
    position: relative
    z-index: 2
  &_item
    width: 14.28%
    flex: 0 0 14.28%
    padding: 0 14px
    .label
      font-size: 14px
      color: #fff

.select, .v-select
  border: none
  outline: none
  height: 40px
  border-radius: 3px
  width: 100%
  cursor: pointer
  background-color: #fff
  .vs__dropdown-toggle
    height: 100%
  .vs__clear
    display: flex

</style>
<script>
import Vue from 'vue'
import vSelect from 'vue-select'
import 'vue-select/dist/vue-select.css'

Vue.component('v-select', vSelect)
export default {
  data() {
    return {
      options: [
        'Категория 1',
        'Категория 2',
        'Категория 3'
      ]
    }
  },
}
</script>
