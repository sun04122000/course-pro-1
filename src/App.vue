<template>
  <div id="app">
    <TopScreen />
  </div>
</template>

<script>
import TopScreen from './components/TopScreen.vue';

export default {
  name: 'App',
  components: {
    TopScreen
  },
  data(){
    return{
      
    }
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body{
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}
</style>
