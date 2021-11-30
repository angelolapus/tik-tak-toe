<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>-->

    <WelcomeScreen title="Tik-tak Toe" gameScreenBtnCaption="Start"/>
  </div>
</template>

<script>

  import  WelcomeScreen  from './components/WelcomeScreen.vue';

  export default {
    name: 'App',
    components: {
      WelcomeScreen
    }
  } 

</script>

<style>
body{
  background-color: #FFCC33;
}
</style>
