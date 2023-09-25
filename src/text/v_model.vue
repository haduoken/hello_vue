<script setup>
import { ref } from 'vue'

const text = ref('')

</script>


<template>
  <input v-model="text" placeholder="sdf">
  <p>text is {{ text }}</p>
</template>