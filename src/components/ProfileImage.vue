<script setup>
const props=defineProps({
  value: {
    type: String
  }
})
</script>

<template>
<img
      :src="value"
      class="profile"
      alt="profile"
    />

</template>

<style scoped>
</style>