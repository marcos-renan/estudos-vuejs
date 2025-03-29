<!--Diretiva :class-->
<script setup>
    let validacao = true;
    let validacao2 = false;
</script>

<style>
    .ok {
        color:green;
    }

    .falha {
        color: red;
    }
</style>

<template>
    <h1 :class="validacao ? 'ok' : 'falha'">
        Diretiva :class
    </h1>
    <h1 :class="validacao2 ? 'ok' : 'falha'">
        Diretiva :class 2
    </h1>
</template>