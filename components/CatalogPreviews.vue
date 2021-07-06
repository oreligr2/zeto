<template>
  <div class="container">
    <div class="catalog_preview--items">
      <div class="catalog_preview--wrapper">
        <CatalogPreview />
      </div>
      <div class="catalog_preview--wrapper">
        <CatalogPreview :isNew="true" />
      </div>
      <div class="catalog_preview--wrapper">
        <CatalogPreview />
      </div>
      <div class="catalog_preview--wrapper">
        <CatalogPreview :isHit="true" />
      </div>
      <div class="catalog_preview--wrapper">
        <CatalogPreview />
      </div>

    </div>
  </div>
</template>
<style lang="sass">
.catalog_preview
  &--items
    display: flex
    margin-right: -14px
    margin-left: -14px
    padding: 30px 0
  &--wrapper
    padding-left: 14px
    padding-right: 14px
    width: 20%
    flex: 0 0 20%

</style>
