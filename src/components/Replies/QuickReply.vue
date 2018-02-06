<template>
  <div class="quick-reply">
    <span>
      <slot></slot>
    </span>
  </div>
</template>
<script>
export default {
  name: 'quick-reply',
  data() {
    return {
      isRed: true
    }
  }
}
</script>
<style lang="stylus">
.quick-reply
  background-color #cccccc
  border-radius 1.3em
  overflow hidden
  padding 10px 15px
</style>
