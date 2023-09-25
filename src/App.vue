<script setup>
import { ref } from 'vue';
// 创建ref对象
const count = ref(0)

// 定义自己的函数
function incre() { count.value++ }

</script>

<template>
  <!-- 监听DOM的事件使用v_on: 可以简写为@ -->
  <button @click="incre">{{ count }}</button>
</template>