<template>
  <div id="footer">
    <span>writter by {{this.author}}</span>
  </div>
</template>

<script>
export default {
  data () {
    return {
      author: 'Sam Zhou'
    }
  }
}
</script>

<style lang="stylus" scoped>
  #footer
    margin-top 40px
    text-align center
    color #bfbfbf
    font-size 10px
    text-shadow 0px 1px 0px 1px
</style>
