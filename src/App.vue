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
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }

  body {
    background-image: url(assets/patitas_felizes_fundo_resized_clear.jpg);
    background-size: 100%;
    background-repeat: no-repeat;
    background-color: #9EE8E4;
  }
  
  .main-container{
    padding: 50px;
  }

  
  #aboutUs{
    margin-left: 540px;
    color: white;
    background-color: #9EE8E4;
    border-radius: 10px;
    padding: 10px;
    width: 100px;
  }
  h1{
    text-align: center;
    font-size: 40px;
    margin-bottom: 50px;
  }

  a {
    color: #222;
    text-decoration: none;

  }
</style>