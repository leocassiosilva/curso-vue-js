<script setup>
    //variável
    import { ref } from "vue";


    let texto = ref('');


</script>


<template>
    <input type="text" v-model="texto" placeholder="Digite algo">
    <p>{{texto}}</p>

</template>