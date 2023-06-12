<template>
  
  <H1 id="title">
      vous trouverez en dessous de ça une page web en construction
  </H1>

  <div id="bodyPage">
    
    
    
    <BackgroundColorChanger/>
    <LetterCounter/>
  </div>
  
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
text-align: center;
}

#bodyPage {
  display: flex;
  justify-content: space-evenly;
  border: 2px plum solid;
  padding: 7px;
}

body{
  background-color: aquamarine;

}

div{
  width: fit-content;
  border: 3px solid black;
}


</style>
