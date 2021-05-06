<template>
<Google></Google>
</template>

<script>
import Google from './components/Google.vue'

export default {
  name: 'App',
  components: {
    Google
  }
}
</script>

<style>
*{

  margin:0;

  padding:0;

}

html {

  width:100vw;

  height:100vh;

}



body{

  width:100%;

  height:100%;

}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
