//Diretivas v-else-if e v-else
<!--CODIGO-->
<script setup>
    let exibir = true;
    let media = 9;
</script>

<!--HTML-->
<template>
    <h1 v-if="exibir">Olá Mundo!</h1>
    <p v-if="media >= 7">Aprovado(a)</p>
    <p v-else-if="media >=5">Recuperação</p>
    <p v-else>Reprovado(a)</p>
</template>