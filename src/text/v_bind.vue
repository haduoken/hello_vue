<script setup>
import { ref } from 'vue';
// 创建ref对象
const title_class = ref('title')

</script>

<template>
  <!-- v_bind: 简写为: -->
  <h1 :class="title_class">make me red</h1>
</template>

<style>
/* css 语法里面.title 代表了类选择器, class=title */
.title {
  color: red
}
</style>