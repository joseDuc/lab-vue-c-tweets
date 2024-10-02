<script setup>
const props=defineProps({
  value: {
    type: String
  }
})
</script>

<template>
    <p class="message">
        {{ value }} 
      </p>
</template>

<style scoped>
</style>