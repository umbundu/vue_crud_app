<template>
  <footer>
    <h1>{{ message }}</h1>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {
      message: 'testdriven.io 2019'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
footer {
  margin: auto;
}
</style>