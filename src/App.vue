<template>
  <div id="app">
      <router-view/>
  </div>
</template>

<script>
  export default {
    name: 'App'
  }
</script>


<style lang="sass">
@import "assets/styles/sass/main.scss"
@import "assets/fonts/latofonts.css"
@import "assets/styles/css/util.css"
@import "../node_modules/vue-multiselect/dist/vue-multiselect.min.css"
</style>
