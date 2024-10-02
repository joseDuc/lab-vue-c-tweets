<script setup>
const props=defineProps({
  value: {
    type: String
  }
})
</script>

<template>
    <span class="timestamp">{{value}}</span>
</template>

<style scoped>
</style>