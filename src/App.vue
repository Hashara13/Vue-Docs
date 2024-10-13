<script setup>
import {ref} from 'vue'
const count=ref(0)
function increment(){
  count.value++
}
</script>
<template>
  <h1 @click="increment">Count is : {{ count }} </h1>
</template>
