<template>
  <div class="generic-template">
    <div class="wrapper">
      <slot></slot>
    </div>
  </div>
</template>
<script>
export default {
  name: 'generic-template'
}
</script>
<style lang="stylus">
.generic-template
  width 320px
  min-height 120px
  background-color #cccccc
  border-radius 1.32em
  overflow hidden

</style>


