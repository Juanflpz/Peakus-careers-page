<template>
  <div id="app" class="container-fluid">
    <!--<img alt="Vue logo" src="./assets/logo.png">-->
    <!--<HelloWorld msg="Hola pepito"/>-->
    <MainNav></MainNav>
    <div class="row">
      <div class="col-lg-auto" style="width:90px">
        <SideNav></SideNav>
      </div>
      <div class="col-lg-11 flex-grow-1 p-0">
        <JobCards></JobCards>
      </div>
    </div>
    
    
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import JobCards from './components/JobCards.vue'
import SideNav from './components/SideNav.vue'
import MainNav from './components/MainNav.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld,
    JobCards,
    SideNav,
    MainNav
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 20px;
}

.bold {
  font-weight: bold;
}

.shadows {
  background-color: white;
}

.logos{
  padding-right: 60px;
}

.shadows:hover {
  box-shadow: 5px 5px 5px rgba(134, 134, 134, 0.3), /* Derecha, abajo, e izquierda */
              0px -5px 0px rgba(134, 134, 134, 0); /* Aproximadamente 5px por debajo del top */
  transition: box-shadow 0.3s ease; /* Transición para suavizar el cambio */
}
</style>
