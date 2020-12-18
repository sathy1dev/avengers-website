<template>
  <div id="app">
  <Navbar/>
  <herotext/>
  </div>
</template>

<script>

import Navbar from './components/Navbar.vue'
import herotext from './components/herotext.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    herotext
  }
}
</script>

<style>
 #app
 {
    height: 100vh;
  width: 1464px; /* here you can set your maximum 12 cols + 11 gaps width */
  margin: 0 auto; /* this will make .wrapper centered */
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 16px; /* like 40px, but the snippet is very small */
  overflow: hidden;
  
  }
  body{
  background-image: url('./assets/bg.png');
  background-repeat: no-repeat;
  background-attachment: fixed;  
  background-size: 100% 100vh;
  overflow-x: hidden;
  overflow-y: hidden;
  
  }

  *
  {
    list-style-type: none;
    text-decoration: none;
    padding: 0;
    margin: 0;
  }
</style>
