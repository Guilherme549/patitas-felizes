<template>
  <header>
    <span id="logo"></span> 
    <nav class="navigation">
      <router-link to="/" class="nav-link">Home</router-link>
      <router-link to="/about" class="nav-link">Sobre nós</router-link>
      <router-link id="adocao" to="/AnimaisParaAdocao" class="nav-link">Animais Para Adoção</router-link> 
    </nav>
  </header>
  <router-view/>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>
header {
    padding: 10px 0; 
    display: flex;
    justify-content: space-between; 
    align-items: center;
}

#logo {
    background-image: url('../assets/logoPezitos.png'); 
    background-size: contain;
    background-repeat: no-repeat;
    border-radius: 50%;
    margin-left: 30px;
    width: 100px; 
    height: 100px; 
}

.navigation {
    display: flex;
    gap: 25px; 
    margin-right: 30px;
}

.nav-link {
    text-decoration: none;
    color: #222; 
    font-weight: bold;
    transition: color 0.1s ease;
    padding: 15px 15px; 
    border-radius: 30px;
}

.nav-link:hover,
.nav-link:focus {
    background-color: #FFAD60; 
    color: white;
}

#adocao {
    background-color: #FFAD60;

}
</style>
