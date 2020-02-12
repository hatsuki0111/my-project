<template>
  <div id="app" class="body">
    <myheader></myheader>
    <img src="./assets/icon.png">
    <router-view/>
  </div>
</template>

<script>
import myheader from './components/myheader'

export default {
  name: 'App',
   components: {
    myheader
  },
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
img{
  margin-top: 60px;
  margin-bottom: 10px;
  border-radius: 50%; 
  max-width: 100%;
  height: 200px;
  width: 200px;
}
.body{
    background-color: #000011;
}

</style>
