<template>
  <!-- Application -->
  <div p="4">
    <span un-text="white">Hello To Alaa New App</span>
    <UiButton @click="app.toggleRunning()">Exit App</UiButton>
  </div>
  <UiButton color="primary"> Botton </UiButton>
</template>

<script setup>
const props = defineProps({
  app: {
    type: Object,
    required: true,
  },
});
</script>
