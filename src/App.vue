<template>
  <Header></Header>
 
</template>

<script>
  import Header from "./components/Header.vue"
  export default{
    components: {
      Header
    }
  }
</script>


<style>
  * {
    padding: 0;
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
  }

  body {
    background-image: url(assets/patitas_felizes_fundo_resized_clear.jpg);
    background-size: 100%;
  }

  a {
    color: #222;
    text-decoration: none;
    margin: 12px;
  }
</style>