<script setup>
    //vetor
    let nomes = ['Alice', 'Bob', 'Carol', 'Dave', 'Eve'];

</script>

<template>

    <ul>
        <li v-for="nome in nomes" :key="nome">
            {{ nome }}
        </li>
    </ul>


</template>