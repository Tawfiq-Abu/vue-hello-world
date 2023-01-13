<template>
 <div>
  <div>hello {{ name }}, on {{ date }} at {{ location }} i met you and i was so happy</div>

  <div v-text="channel"></div>
  <h2 v-bind:id="headingId">Heading</h2>
  <button v-bind:disabled="isDisabled">Disabled</button>
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
      location : 'Aboabo',
      channel : '<b> tawfiq </b>',
      headingId : 'heading',
      isDisabled: true
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
