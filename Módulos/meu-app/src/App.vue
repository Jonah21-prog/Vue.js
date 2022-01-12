<template>
  <div id="app">
    <h1>Bem vindo ao meu projeto</h1>
    <button @click="entrar" >Entrar</button>
    <usuario :nome='nome' />
  </div>
</template>

<script>
import Usuario from "./components/Usuario.vue";

export default {
  name: "App",
  components: {
    Usuario
  },
  data(){
    return{
      nome: 'Sujeito programador'
    }
  },
  methods:{
    entrar(){
      this.nome = 'Curso Vue.js'
    }
  }
}
</script>

