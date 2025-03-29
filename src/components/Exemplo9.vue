<!--Eventos de teclado-->

<!--CODIGO-->
<script setup>
    function mensagem(){
            alert('Trabalhando com eventos de teclado.')
        }
</script>

<!--HTML-->
<template>
    <h1>Eventos de clique</h1>
    <input type="text" @keyup.enter="mensagem" placeholder="Pressione ENTER aqui">
    <input type="text" @keyup.space="mensagem" placeholder="Pressione SPACE aqui">    <input type="text" @keyup.esc="mensagem" placeholder="Pressione ESC aqui">
</template>
