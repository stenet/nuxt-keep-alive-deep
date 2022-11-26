<template>
  <div>data</div>
</template>

<script setup lang="ts">
import { onBeforeUnmount, onUnmounted, onMounted, ref } from 'vue';
const visible = ref(true);
onBeforeUnmount(() => {
  debugger;
});
onMounted(() => {
  console.log('mounted');
});
onUnmounted(() => {
  console.log('unmounted');
});
</script>
