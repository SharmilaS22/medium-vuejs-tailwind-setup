<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <Navbar v-bind:links="['Home', 'About', 'Contact']"/>
  <Login />
  <Footer />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar'
import Login from './components/Login'
import Footer from './components/Footer'


export default {
  name: 'App',
  components: {
    // HelloWorld,
    Navbar,
    Login,
    Footer
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>

<style src="./index.css" />