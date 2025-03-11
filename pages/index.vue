<script lang="ts" setup>
const handleMessage = () => {
  message.info("This is a normal message");
};
</script>
<template>
  <a-button @click="handleMessage"> button </a-button>
</template>
