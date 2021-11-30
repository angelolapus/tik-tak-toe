<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>-->

    <WelcomeScreen title="Tik-tak Toe" gameScreenBtnCaption="Start"/>
    <Board></Board>
  </div>
</template>

<script>

  import  WelcomeScreen  from './components/WelcomeScreen.vue';
  import Board from './components/Board.vue';

  export default {
    name: 'App',
    components: {
      WelcomeScreen,
      Board
    }
  } 

</script>

<style>
body{
  background-color: #FFCC33;
}
</style>
