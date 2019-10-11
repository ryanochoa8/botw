<template>
  <div class="home">
    <h1>Zelda Breath of the Wild Recipe API</h1>
    <SearchBar></SearchBar>

  </div>
</template>

<script>
  // @ is an alias to /src
  import SearchBar from '../components/SearchBar.vue'


  export default {
    name: 'home',
    components: {
      SearchBar
    }
  }
</script>