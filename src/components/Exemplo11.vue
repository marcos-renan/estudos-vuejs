PreventDefault

<script setup>

    function validaForm(event){
        alert("Formulário enviado")
        //so permite redirecionamento se os campos estiverem preenchidos
        event.preventDefault();
        
    }
</script>

<template>
    <form action="httpw://www.google.com" @submit="validaForm">
        <input type="submit" value="Enviar">
    </form>
</template>