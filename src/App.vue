<script setup>
import HelloWorld from './components/HelloWorld.vue';
import Yo from './components/Yo.vue';
import confetti from 'canvas-confetti';
confetti();
</script>

<template>
  <div>
    <h1>Welcome to jeremyrepo so</h1>
    <HelloWorld msg="You did it!" />
    <Yo msg="From YO!" />
  </div>
</template>

<style scoped></style>
