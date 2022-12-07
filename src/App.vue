<template>

<p>voici un peu de texte </p>

<BackgroundColorChanger/>
</template>

<script>
import BackgroundColorChanger from './components/BackgroundColorChanger.vue'

export default {

  components: {
    BackgroundColorChanger
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
/* vous trouverez apres les tests css que j'ai fait */
  background-color: rgb(13, 123, 219);
  width: 100%;
  height: auto;
}
</style>
