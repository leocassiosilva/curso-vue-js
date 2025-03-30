<script setup>

    function validarFormulario(){
        alert("Formulário enviado com sucesso!");
        // Aqui você pode adicionar a lógica para processar o formulário
    }

</script>

<template>
    <form @submit="validarFormulario">
        <input type="submit" value="Enviar Formulário">
    </form>
</template>