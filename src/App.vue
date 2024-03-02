<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png">-->
    <!--<HelloWorld msg="Hola pepito"/>-->
    <JobCards></JobCards>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import JobCards from './components/JobCards.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld,
    JobCards
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
