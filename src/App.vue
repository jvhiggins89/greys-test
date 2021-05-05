<template>
  <div id="app">
    <Navbar></Navbar>
    <router-view/>
    <AppBottomDataFrame></AppBottomDataFrame>
  </div>
</template>

<script>
import Navbar from "./components/Navbar"
import AppBottomDataFrame from "./components/AppBottomDataFrame.vue"

export default {
  Name: "App",
  components:{
    Navbar,
    AppBottomDataFrame
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif ;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: #F4E8E8;
}

</style>
