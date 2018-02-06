<template>
  <div id="app">
    <Header/>
    <conversation></conversation>

  </div>
</template>

<script>
import Header from './components/Header'
import Conversation from './components/Conversation'

export default {
  name: 'App',
  components: {
    Header,
    Conversation
  }
}
</script>

<style lang="stylus">
body {
  width 100%
  height 100%
  overflow hidden
  margin 0
  padding 0
}
#app {
  font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
  width 638px;
  margin: 0 auto
  height: 100vh
  border-left 1px solid #ccc
  border-right 1px solid #ccc
  box-sizing border-box
  
}
</style>
