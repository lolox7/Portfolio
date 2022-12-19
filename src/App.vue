<template>
  <HeaderPrincipal/>
  <div id="bodyPage">
    <BackgroundColorChanger/>
    <LetterCounter/>
  </div>
  
</template>

<script>
import HeaderPrincipal from './components/HeaderPrincipal.vue';
import BackgroundColorChanger from './components/BackgroundColorChanger.vue'
import LetterCounter from './components/LetterCounter.vue';

export default {

  components: {
    HeaderPrincipal,
    BackgroundColorChanger,
    LetterCounter
}
}
</script>

<style>
#app {
text-align: center;
}

#bodyPage {
  display: flex;
  justify-content: space-evenly;
  border: 2px plum solid;
  padding: 7px;
}

/* vous trouverez apres les tests css que j'ai fait */
  /* width: 100%;
  height: auto; 
  display: flex;
}

body{
  background-color: aquamarine;
  display: flex;
}

div{
  width: fit-content;
  border: 3px solid black;
}
*/

</style>
