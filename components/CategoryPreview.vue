<template>
  <a href="" class="category_preview">
    <div class="category_preview--img">
      <img src="../assets/icons/categories/notebook.svg" alt="">
    </div>
    <div class="category_preview--title">
      {{ title }}
    </div>
    <div class="category_preview--arrow">
      <svg width="6" height="8" viewBox="0 0 6 8" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M0.333985 7.05666L3.63181 4L0.333984 0.943344L1.35172 -4.44868e-08L5.66732 4L1.35172 8L0.333985 7.05666Z" fill="black"/>
      </svg>
    </div>
    <div class="category_preview--children">
      <a href="" class="category_preview--child" v-for="child in children">
        <span>{{ child.title }}</span>
        <div class="category_preview--arrow">
          <svg width="6" height="8" viewBox="0 0 6 8" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M0.333985 7.05666L3.63181 4L0.333984 0.943344L1.35172 -4.44868e-08L5.66732 4L1.35172 8L0.333985 7.05666Z" fill="black"/>
          </svg>
        </div>
      </a>
    </div>
  </a>
</template>
<style lang="sass">
.category_preview
  padding: 15px 10px 15px 25px
  background: #FFFFFF
  box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1)
  border-radius: 3px
  display: flex
  align-items: center
  position: relative
  color: #000
  transition: 0.3s
  width: 100%
  &:hover
    width: 120%
    z-index: 1
    text-decoration: none
    .category_preview--children
      display: block
    > .category_preview--arrow
      transform: rotate(90deg)
      background-color: #00B341
      path
        fill: #fff


  &--title
    margin-left: 17px
    line-height: 20px
    font-weight: 500
    margin-right: 20px
  &--arrow
    background: #FFFFFF
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1)
    border-radius: 3px
    flex: 0 0 20px
    width: 20px
    height: 20px
    display: flex
    align-items: center
    justify-content: center
    transition: 0.3s
    path
      transition: 0.3s
  &--children
    display: none
    padding: 20px 0
    position: absolute
    z-index: 1
    width: 100%
    left: 0
    top: 100%
    background-color: #fff
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1)
  &--child
    display: flex
    justify-content: space-between
    width: 100%
    height: 50px
    align-items: center
    color: #000000
    font-weight: 500
    padding-left: 20px
    padding-right: 20px
    position: relative
    transition: 0.3s
    &::before
      content: ''
      width: 2px
      height: 30px
      position: absolute
      background: #00B341
      border-radius: 3px
      left: 0
      transition: 0.3s
    &:hover
      background: #EFEFEF
      padding-left: 40px
      text-decoration: none
      &::before
        left: 20px
      .category_preview--arrow
        background-color: #00B341
        path
          fill: #fff


</style>
<script>
export default {
  props: ['title', 'imgSrc', 'children'],
  data() {
    return {

    }
  }
}
</script>
