<script>
export default {
  name: 'Header',
  data(){
    return {
      blogTitle: 'This is a simple message'
    }
  },
  mounted(){
    console.log('it is mounted')
  },
  render(createElement){
    return createElement('h1', this.blogTitle)
  }
}
</script>
<style lang="stylus">
.Header 
  border-bottom 1px solid #ccc
  background-color #f8f9f9
  padding: 15px 0

  h1
    font-size: 28px
    font-weight 200
    margin 0

  p
    font-size 16px
    margin 0
</style>

