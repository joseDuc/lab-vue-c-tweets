<script setup>
const props=defineProps({
  value: {
    type: Object
  }
})
</script>

<template>
    <span class="user">
        <span class="name">{{value.name}} </span>
        <span class="handle">{{ value.handle }} </span>
    </span>
</template>

<style scoped>
</style>