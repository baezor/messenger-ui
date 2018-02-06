<template>
    <div>
        <div class="conversation">
          <div class="bot-avatar">
            <img src="../assets/logo.png" alt="Bot Image">
          </div>
        <quick-reply>This is a quick reply</quick-reply>
      
      </div>

      <div class="conversation">
          <div class="bot-avatar">
            <img src="../assets/logo.png" alt="Bot Image">
          </div>
        <quick-reply>This is a quick reply</quick-reply>
      </div>
    
    </div>
</template>

<script>
import QuickReply from './Replies/QuickReply'

export default {
  name: 'conversation',
  components: {
    QuickReply
  }

}
</script>
<style lang="stylus">

.conversation
  display flex
  align-items center

.bot-avatar
  width 36px
  height 36px
  display inline-flex
  border-radius: 50%
  overflow hidden
  background-color #222

  img 
    width 100%
    height auto
</style>

