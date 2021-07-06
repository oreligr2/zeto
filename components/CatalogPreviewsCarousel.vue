<template>
  <div class="container">
    <VueSlickCarousel class="catalog_preview--carousel" :arrows="true" :dots="false" :slidesToShow="5">
      <div class="catalog_preview--wrapper">
        <CatalogPreview />
      </div>
      <div class="catalog_preview--wrapper">
        <CatalogPreview />
      </div>
      <div class="catalog_preview--wrapper">
        <CatalogPreview />
      </div>
      <div class="catalog_preview--wrapper">
        <CatalogPreview />
      </div>
      <div class="catalog_preview--wrapper">
        <CatalogPreview />
      </div>
      <div class="catalog_preview--wrapper">
        <CatalogPreview />
      </div>
      <div class="catalog_preview--wrapper">
        <CatalogPreview />
      </div>
    </VueSlickCarousel>
  </div>
</template>
<style lang="sass">
.catalog_preview--carousel
  margin-bottom: 15px
  .slick-list
    padding-bottom: 15px
  .slick-arrow
    width: 50px
    height: 50px
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1)
    border-radius: 3px
    background-color: #fff!important
    z-index: 9
    background-image: url(./assets/icons/arrow-left.svg)!important
    background-repeat: no-repeat
    background-position: 50%
    &::before
      display: none
    &.slick-prev
      left: -65px
    &.slick-next
      right: -65px
      transform: rotate(180deg)
      top: calc(50% - 25px)
</style>
<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
  name: 'CatalogPreviewsCarousel',
  components: { VueSlickCarousel },
}
</script>
