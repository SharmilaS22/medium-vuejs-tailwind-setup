<template>
  <Navbar v-bind:links="['Home', 'About', 'Contact']"/>
  <Login />
  <Footer />
</template>

<script>
import Navbar from './components/Navbar'
import Login from './components/Login'
import Footer from './components/Footer'


export default {
  name: 'App',
  components: {
    Navbar,
    Login,
    Footer
  }
}
</script>

<style src="./index.css" />