<!--Script-->
<script setup>
    //Variáveis
    let exibir = true; 


    let media = 2; 


</script>


<!--Template-->
<template>
<h1 v-if="exibir">

  Olá, Mundo!!  

</h1>

<p v-if="media >= 7">Aprovado (a)!</p>
<p v-else-if="media >=5">Em exame</p>
<p v-else>Reprovado (a)</p>

</template>