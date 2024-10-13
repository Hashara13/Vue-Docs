<script setup>
import {ref} from 'vue'
const message=ref('Reactive dynamic message')
</script>

<template>
  <h1>{{message}}</h1>
</template>