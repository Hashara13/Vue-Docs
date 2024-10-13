<!-- <script setup>
import {ref} from 'vue'
const text=ref('')
function Ontype(e){
  text.value=e.target.value
}
</script>
<template>
  <input :value="text" @input="Ontype"  type="text">
  <h1>{{ text }}</h1>
</template> -->

<script setup>
import {ref} from 'vue'
const text=ref('')

</script>
<template>
  <input v-model="text" type="text">
  <h1>{{ text }}</h1>
</template>

