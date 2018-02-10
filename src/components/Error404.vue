<template>
  <div class="main">
    <h1>Error 404</h1>
    <button class="goHome" v-on:click="$router.push('/')">Go Home</button>
  </div>
</template>

<script>
  export default {
    name: 'error',
    data () {
      return {}
    }
  }
</script>

<style scoped lang="less">
  .main {
  }
</style>
