<template>
  <!--<div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
-->
    <Cabecera/>
   
  <router-view/>
</template>



<script>
// @ is an alias to /src
import Cabecera from '@/components/Cabecera.vue'



export default {
  name: 'cabecera',
  components: {
    Cabecera

   }
}

</script>


<style>


*{
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width:100%;
  padding: 0px;
  margin: 0px;
  margin: auto;
}

#nav {
  padding: 20px;
  
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  padding: 0 15px;
  margin: 0 25px;
  border-radius:20px;
  transition: ease .3s;
}

#nav a:hover {
  color:#fff;
  background: #ff0033;
  margin: 0 25px;
  padding: 0 15px;
 
}

#nav a.router-link-exact-active {  
  color: #fff;
  background: #ff0033;
  margin: 0 25px;
  padding: 0 15px;

}

</style>