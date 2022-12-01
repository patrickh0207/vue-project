<script setup lang="ts">
  import { ref } from 'vue';

  let myVar = ref("Hello World!")

  const myFunc = () => {
    myVar.value = "I clicked a button!"
  }
</script>

<template>
 <h1>{{ myVar }}</h1>
 <button @click="myFunc">click me</button>
</template>

<style scoped>

</style>
