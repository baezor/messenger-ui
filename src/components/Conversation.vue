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
        <generic-template>

        </generic-template>
      </div>
    
    </div>
</template>

<script>
import QuickReply from './Replies/QuickReply'
import GenericTemplate from './GenericTemplate'

export default {
  name: 'conversation',
  components: {
    QuickReply,
    GenericTemplate
  }

}
</script>
<style lang="stylus">

.conversation
  display flex
  align-items center
  margin 10px 0

.bot-avatar
  width 36px
  height 36px
  margin 0 10px
  display inline-flex
  border-radius: 50%
  overflow hidden
  background-color #222
  align-self flex-end

  img 
    width 100%
    height auto
</style>

