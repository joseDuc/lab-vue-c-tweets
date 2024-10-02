<script setup>
const props=defineProps({
  values: {
    type: Array
  }
})
</script>

<template>
    <div class="actions" >
        <!-- Font Awesome icons -->
        <!--<i v-for="(value, index) in values" :key="index">{{ value }}</i>-->
         
        <i class="far fa-comment"></i>
        <i class="fas fa-retweet"></i>
        <i class="far fa-heart"></i>
        <i class="fas fa-share"></i>
    </div>
</template>

<style scoped>
</style>