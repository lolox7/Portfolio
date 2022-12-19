<template>
    <div>
        <header id="baseHeader">
            <img src="../assets/logo.png" alt="logo" id="logo">
            <p id="headerText">
                you will find under this header the rest of a building page
            </p>

        </header>
    </div>
</template>


<script>

</script>


<style>

#baseHeader{
    border: dotted grey 2px;
    display: flex;
    align-content: center;
    grid-row: 1;
    grid-column: 1;
}

#logo {
    width: 50px;
    justify-content: flex-start;
}

#headerText {
    text-align: center;
    /* border: 2px solid black; */
}


/* p {
} */

</style>