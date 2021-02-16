<template>
  <main class="container restaurant">
    <h1>Restaurants:</h1>
 <app-restaurant-info/>
</main>
</template>

<script>
  import appRestaurantInfo from '../components/AppRestaurantInfo.vue'

  export default {
        name: "Restaurants.vue",
    components: {
          appRestaurantInfo
    }
    }
</script>

<style scoped>

</style>
