<script setup>
import { onMounted, ref } from 'vue'

const pElementRef = ref(null)
onMounted(() => {
  pElementRef.value.textContent = 'mounted!'
})
</script>

<template>
  <p ref="pElementRef" @click="onMounted">Hello</p>
</template>
