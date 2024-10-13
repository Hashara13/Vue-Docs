<script setup>
import {ref} from 'vue'
const message=ref('Dynamic Binding')
</script>
<template>
  <h1>{{ message }}</h1>
</template>