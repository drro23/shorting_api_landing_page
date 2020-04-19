<template>
  <div class="container">
    <NavBar />
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import NavBar from '~/components/NavBar.vue'

export default {
  components: {
    Logo,
    NavBar
  },
  head: {
    titleTemplate: 'Shorting api landing page challenge',
    meta: [
      { charset: 'utf-8'}
    ]
  }
}
</script>

<style>
.container {
  width: 80%;
  margin: 0 auto;
}
</style>
