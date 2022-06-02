<template>
  <div>
    <h1> {{ tituloh1 }} </h1>
    <img v-bind:src="images.url" v-bind:alt="images.descricao">
  </div>
</template>

<script>
export default {
  data(){
    return{
      tituloh1: 'Qualquer frase',
      images: {
        url:'https://images.unsplash.com/photo-1570964251416-6ae7f9b8db47?crop=entropy&cs=tinysrgb&fm=jpg&ixlib=rb-1.2.1&q=80&raw_url=true&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=693',
        descricao: 'ovelha'
      }
    }
  }
}
</script>

<style>
</style>
