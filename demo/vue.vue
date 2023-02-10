<template>
    <h1>Hello {{ textStr }}</h1>
</template>

<script setup lang="ts">
import { ref } from 'vue'
const textStr = ref('World')
</script>