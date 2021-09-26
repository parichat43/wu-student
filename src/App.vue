<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome" name="Parichat Chusit"/>
  <input type="text" v-model="message" placeholder="enter">
  <p>Message is: {{message}}</p>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data(){
    return {
      message:""
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
