<!--Script-->
<script setup>
    //variavel
    let validacao = true; 

</script>

<!--Template-->
<style>
    .ok {
        color: green;
    }

    .falha {
        color: red;
    }

</style>


<template>
    <p :class="validacao ? 'ok': 'falha'">Utilizando a diretiva class</p>
</template>