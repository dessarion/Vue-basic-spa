<template>
  <div id="app">
    <Nav />
    <div class="container">
      <router-view />
    </div>
  </div>
</template>

<script>
import Nav from '@/components/Nav'
export default {
  name: 'app',
  components: {
    Nav
  },
}
</script>

<style lang="scss">
 @import "~materialize-css/dist/css/materialize.min.css"
</style>
