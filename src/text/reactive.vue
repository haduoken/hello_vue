<script setup>

import { reactive } from 'vue';

// 将对象设置为反应性
const counter = reactive({ count: 0 })

console.log(counter.count)
counter.count++

import { ref } from 'vue';
// 将普通的字符串设置为反应性
const message = ref('hello world')
console.log(message.value)
message.value = 'Changed'

</script>

<template>
  <h1>{{ message }}</h1>
  <h1>count is : {{ counter.count }}</h1>
</template>