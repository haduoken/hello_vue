<script setup>
import { ref } from 'vue'

const condi = ref('')
function toggle() {
  condi.value = !condi.value
}
</script>

<template>
  <button @click="toggle"></button>
  <p v-if="condi">Vue is awesome</p>
  <p v-else>On no</p>
</template>