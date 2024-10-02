<script setup>
import { defineProps } from 'vue';
import ProfileImage from "./ProfileImage.vue"
import User from './User.vue';
import Timestamp from './Timestamp.vue';
import Message from './Message.vue';
import Actions from './Actions.vue';
const props=defineProps({
  tweet: {
    type: Object
  }
})


</script>
<template>
  <div class="tweet">
    <ProfileImage :value="tweet.user.image"/>

    <div class="body">
      <div class="top">
        <User :value="tweet.user"/>
        <Timestamp :value="tweet.timestamp"/>
      </div>
      <Message :value="tweet.message"/>
      <Actions/>
    </div>

    <i class="fas fa-ellipsis-h"></i>
  </div>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
