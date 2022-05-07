<template>
<section>
  <img src="/src/assets/logo.png" alt="">
  <p>{{msg}}</p>
</section>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
