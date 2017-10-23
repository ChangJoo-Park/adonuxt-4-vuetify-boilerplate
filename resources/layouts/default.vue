<template>
  <v-app>
    <main>
      <v-container fluid>
        <nuxt/>
      </v-container>
    </main>
    <v-footer app></v-footer>
  </v-app>
</template>

<script>
  const MyFooter = () => import('~/components/MyFooter')

  export default {
    name: 'layout-default',
    components: {
      MyFooter
    }
  }
</script>

<style>
</style>
