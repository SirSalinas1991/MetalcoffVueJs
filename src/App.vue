<template>
  <nav>
    
    <router-link to="/">  Home  </router-link> 
    <router-link to="/about">  About  </router-link>
    <router-link to="/clientes">  Cliente  </router-link>

    

  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  background-color: rgba(35, 53, 85, 0.726);

}

nav {

  font-weight: bold;
  color: #ffffff;
 
 }



nav a {
  left: auto;
  font-weight: bold;
  color: #000000;

}

nav a.router-link-exact-active {
  color: #000000;
  margin: auto;
  padding: auto;
}

</style>
