<template>
  <div>
      <button @click="connect">connect</button>
  </div>
</template>
<script setup lang="ts">
const connect = () => {
    new WebSocket('ws://dev.amlglobal.net/chat/ws/39Fo28ftHyDoZQxwMfq8Gd/?token=3de5fab876c9603f37db55449c52ab0b6d30f1ef')
}
</script>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
