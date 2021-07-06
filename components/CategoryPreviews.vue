<template>
  <div>
    <div class="category_preview--items">
      <div class="category_preview--wrapper" v-for="item in items">
        <CategoryPreview
          :title="item.title"
          :imgSrc="item.imgSrc"
          :children="item.children"
        />
      </div>
    </div>
  </div>
</template>
<style lang="sass">
.category
  &_preview
    &--items
      width: 100%
      display: flex
      flex-wrap: wrap
      margin-left: -14px
      margin-right: -14px
      position: relative
      z-index: 2
    &--wrapper
      width: 20%
      flex: 0 0 20%
      padding: 0 14px
      margin-bottom: 26px
</style>
<script>
export default {
  data() {
    return {
      items: [
        {
          title: 'Запчасти для ноутбука',
          imgSrc: '../assets/icons/categories/notebook.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },
        {
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },
        {
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },
        {
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },
        {
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },{
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },{
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },{
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },{
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },{
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },{
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },{
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },{
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },{
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },
        {
          title: 'Запчасти для планшетов',
          imgSrc: '../assets/icons/categories/tablet.svg',
          children: [
            {
              title: 'Процессоры',
            },
            {
              title: 'Матрицы',
            },
            {
              title: 'Мониторы',
            },
            {
              title: 'Клавиатуры',
            },
            {
              title: 'Клавиатуры',
            },
          ],
        },
      ],
    }
  },
}
</script>
