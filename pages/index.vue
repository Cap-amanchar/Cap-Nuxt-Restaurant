<template>
  <main class="container">
    <app-header/>
    <app-restaurant-info/>
  </main>
</template>

<script>
  import  appHeader from '../components/appHeader.vue';
  import appRestaurantInfo from '../components/AppRestaurantInfo.vue'
  export default {
    components: {
      Name: appHeader,
      appRestaurantInfo
    },
  }
</script>

<style>

</style>
