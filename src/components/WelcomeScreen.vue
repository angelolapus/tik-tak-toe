<template>
    <div class="welcomeScreen">
        <h1 class="game-title">{{title}}</h1>
        <button class="game-button">{{gameScreenBtnCaption}}</button>
    </div>
</template>


<script>
export default {
  name: 'WelcomeScreen',
  props:{
      title: String,
      gameScreenBtnCaption: String
  }
} 
</script>

<style lang="scss">
    @import '../styles/variable.scss';
    .welcomeScreen{
        border: 1px solid $color-green;

        .game-title{
            border:1px solid $color-blue;
        }
    }
</style>