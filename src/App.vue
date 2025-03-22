<script>
export default {
  data() {
    return {
      numero: 0,
      nome: "Options Vue"
    }
  },
  methods: {
    adicionarNumero() {
      this.numero++
    },
    removerNumero() {
      this.numero--
    }
  }
}
</script>

<template>
  <h2>{{ nome }}</h2>
  <p>
    {{ numero }}
  </p>
  <button @click="adicionarNumero">+</button>
  <button @click="removerNumero">-</button>
  
</template>

<style scoped>

</style> 
