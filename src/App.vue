<script setup>
import {ref} from 'vue'
const message=ref('title')
</script>
<template>
  <h1 :class="message">Attribute Bindings </h1>
</template>
<style>
.title{
  color: aquamarine;
}
</style>