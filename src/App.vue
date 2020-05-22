<template>
  <div id="app">
    <Navigation/>
    <router-view class="container" />
  </div>
</template>

<style lang="scss">
  $primary: #146136;
  @import "node_modules/bootstrap/scss/bootstrap";
</style>

<script>
  import Navigation from '@/components/Navigation.vue';

  export default {
    name: "app",
    components: {
      Navigation,
    },
  }

</script>
