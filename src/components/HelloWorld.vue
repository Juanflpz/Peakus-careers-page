<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <!--<p>{{ variable1 }}</p>-->

    <!--{{ numero1 }} + {{ numero2 }} = {{ numero1 + numero2 }}-->
    <h1>
      {{ numero1 }}
      <button @click="incrementar">+ Incrementar</button>
      <button @click="decrementar">- Decrementar</button>
    </h1>
    <h2 v-if="numero1 <= 2" style="color: rebeccapurple;">
      TEXTO 1
    </h2>
    <h2 v-else-if="numero1 === 3">
      TEXTO 1.5
    </h2>
    <h2 v-else style="color: burlywood">
      TEXTO 2
    </h2>

    <h3>
      <ul>
        <!--no sirve si hay herramientas duplicadas (sin el index que puede llamarse de cualquier manera)-->
        <!--sirve agregando el index-->
        <li v-for="(herr, index) in herramientas" :key="index">
          {{index}} - {{ herr }}
        </li>
      </ul>
      <!--{{ herramientas[0] }}
      <br>
      <hr>
      {{ herramientas }}-->
    </h3>
    <div style="height: 2vh;"></div>
    <input type="text" placeholder="escribe aquí" v-model="texto">
    <h5>
    {{ texto }}
    </h5>

    <input type="texto2" placeholder="escribe aquí" :value="texto2"> <!--binding-->
    <!--coge el texto2 de la variable si :value, si no se le coloca el : entonces toma el texto plano-->
    <h5>
    {{ texto2 }}
    </h5>

    <input :type="tipo"><br> <!--binding-->
    <button @click="cambiarInput()"> Mostrar/ocultar</button>
    <div style="height: 3vh;"></div>

    <input :type="mostrarContrasena ? 'text' : 'password' "><br> <!--binding-->
    <button @click="cambiarInput2()"> Mostrar/ocultar</button>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return{
      //variable1: "Saludo",
      numero1: 1,
      //numero2: 2
      herramientas: [
        "Alicate", "Hombre solo", "Martillo"
      ],
      texto: "",
      texto2: "texto inicial",
      tipo: "password",
      mostrarContrasena: false
    }
  },
  methods: {
    incrementar(){
      this.numero1++;
    },
    decrementar(){
      this.numero1--;
    },
    cambiarInput() {
      this.tipo = this.tipo === "password" ? "text" : "password"
      /*
      if(this.tipo === "password"){
        this.tipo = "text";
      }
      else{
        this.tipo = "password";
      } */
    },
    cambiarInput2() {
      this.mostrarContrasena = !this.mostrarContrasena
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

<!--single file component con html, script y css-->