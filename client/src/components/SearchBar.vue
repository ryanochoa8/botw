<template>
  <div class="SearchBar col-12">
    <form @submit.prevent="search">
      <input type="text" name="search" placeholder="Search a recipe">
      <button type="submit">Search</button>
    </form>

  </div>
</template>


<script>
  export default {
    name: 'SearchBar',
    data() {
      return {}
    },
    computed: {},
    methods: {},
    components: {}
  }
</script>


<style scoped>

</style>