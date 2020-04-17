<template>
<<<<<<< HEAD
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
=======

  <div id="app">
    <p>Un paragraphe 1</p>
    <img alt="Vue logo" src="./assets/logo.png">
        <p>Un paragraphe 2</p>
    <Composant2 msgbis="Bonjour tout le monde !"/>
    <HelloWorld msg="Hello world !"/>
    <CompForm />
    <p>Un paragraphe 3</p>
>>>>>>> initbis
  </div>
</template>

<script>
<<<<<<< HEAD
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
=======
import Composant2 from './components/Composant2.vue'
import HelloWorld from './components/HelloWorld.vue'
import CompForm from './components/CompForm.vue'
export default {
  name: 'App',
  components: {
    Composant2,
    HelloWorld,
    CompForm
  },

}

>>>>>>> initbis
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
