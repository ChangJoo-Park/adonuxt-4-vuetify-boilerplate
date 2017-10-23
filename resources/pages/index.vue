<template>
  <section class="container">
    <img src="/img/logo.png" alt="Adonuxt logo"/>
    <h1>Universal Vue.js Applications Framework</h1>
    <nuxt-link :to="{ name: 'about' }">About</nuxt-link>
    <v-btn color="primary">Primary</v-btn>
  </section>
</template>

<script>
  export default {
    name: 'page-index'
  }
</script>

<style scoped>
</style>
