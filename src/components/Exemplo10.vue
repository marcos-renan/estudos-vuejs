Evento de submissão
<script setup>
    function validaForm(){
        alert('Formulario enviado');
    }
</script>

<template>
    <form @submit="validaForm">
        <input type="submit" value="Enviar" >
    </form>
</template>