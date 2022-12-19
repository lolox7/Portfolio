<template>
    <div id="colorChanger"> 
        voici le bloc ou le fond d'écran change
        lorsque le bouton est cliqué 
        <button @click="backgroudColorChange"> 
            Changez la couleur ici
        </button>
    </div>    
    
</template>

<script>

export default { 

}

</script>


<style>
#colorChanger {
    width: 45%;
    height: auto;
    background-color: crimson; 
    

}  
button{
    text-align: center;
}
</style>


