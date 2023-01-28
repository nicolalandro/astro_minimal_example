<script setup lang="ts">
import vue from '@astrojs/vue';
import { ref, reactive, onMounted, onUpdated } from 'vue';
let count = ref(0);
</script>

<template>
  <button @click="count++">Vuejs Increment {{ count }}</button>
</template>
