<template>
<div class="flex h-screen m-auto ">
  <div class="m-auto">
  <HomeComponent msg="Welcome to Your Vue.js App"/>
  </div>
</div>

</template>

<script>
import HomeComponent from './components/HomeComponent.vue'




export default {
  name: 'App',
  components: {
    HomeComponent
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
