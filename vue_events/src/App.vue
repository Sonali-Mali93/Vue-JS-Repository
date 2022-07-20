<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <Home/>
  <DataBinding/>
  <InputValues/>
  <RadioAndCheckboxInputValue/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home.vue'
import DataBinding from './components/data_binding.vue'
import InputValues from './components/InputValues.vue'
import RadioAndCheckboxInputValue from './components/chechbox_radio_value.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    Home,
    DataBinding,
    InputValues,
    RadioAndCheckboxInputValue
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
