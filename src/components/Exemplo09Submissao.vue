<script setup>

    function validarFormulario(event){
        alert("Formulário enviado com sucesso!");
        // Aqui você pode adicionar a lógica para processar o formulário
        
        event.preventDefault(); // Impede o envio do formulário para evitar recarregar a página
    }

</script>

<template>
    <form action=""  @submit="validarFormulario">
        <input type="submit" value="Enviar Formulário">
    </form>
</template>