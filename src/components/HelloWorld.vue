<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
const text = ref("")

const rest = (inputValue: string) => {

}
</script>

<template>
  <h1>{{ msg }}</h1>


  <h2>{{ text }}</h2>
  <input @keyup.enter value="text" />

</template>

<style scoped></style>