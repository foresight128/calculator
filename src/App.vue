<template>
  <Home></Home>
</template>

<script>
import Home from './components/Home.vue';

export default {
  components:{
    Home,
  }
};
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
}
body{
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-color: #eee;
  font-size: 24px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
