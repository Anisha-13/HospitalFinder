<template>
<div>
  <FinderLogo />
 

  <router-view />
  

</div>
</template>

<script>

import FinderLogo from './views/FinderLogo.vue'


export default {
  components: {
    FinderLogo,
    
  }
}



</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
   background-color: black;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
