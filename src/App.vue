<template>
  <div id="app">
    <Navbar />
    <router-view/>
  </div>
</template>
<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: 'app',
  components : {
    Navbar
  }
}
</script>
<style lang='scss'>
@import "~bootstrap/scss/bootstrap";

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
