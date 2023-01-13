<template>
 <div>
  hello {{ name }}, on {{ date }} at {{ location }} i met you and i was so happy

  <div v-text="location"></div>
 </div>
 
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  // components: {
  //   HelloWorld
  // }

  data(){
    return {
      name: 'Tawfiq the superman',
      date : '2016-05-01',
      location : 'Aboabo'
    }
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
  margin-top: 60px;
}
</style>
