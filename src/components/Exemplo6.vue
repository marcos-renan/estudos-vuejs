Diretiva v-model
<script setup>
import { ref } from 'vue';

    let texto = ref('');
</script>

<template>
    <input type="text" v-model="texto">
    <h1>{{ texto }}</h1>
</template>