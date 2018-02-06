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

