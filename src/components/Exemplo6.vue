Diretiva v-model
<script setup>
//para criar variavel reatia
import { ref } from 'vue';
    //variavel reativa
    let texto = ref('');
</script>

<template>
    <input type="text" v-model="texto">
    <h1>{{ texto }}</h1>
</template>