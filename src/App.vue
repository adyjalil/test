<template>
  <div id="app">
    <app-header></app-header>
    <app-main></app-main>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import MainVue from './components/Main/Main.vue';


export default {
  components: {
    appHeader: Header,
    appMain: MainVue    
  }
}
</script>

<style>
:root {
  --white: #d6ffe3;
  --green: #69a468;
  --black: #153500;
}

html, body {
  display: grid;
  height: 100%;
  margin: 0;
}


</style>
