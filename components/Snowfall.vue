<script setup>
import { ref, onMounted } from "vue";
import ConfettiGenerator from "confetti-js";

// declare a ref to hold the element reference
// the name must match template ref value
const canvas = ref(null);

onMounted(() => {
  // https://www.npmjs.com/package/confetti-js#options
  const confettiSettings = { 
    target: canvas.value, 
    props: ['circle'], 
    colors: [[150,150,150], [200,200,200], [244,244,244], [255,255,255]],
  };
  const confetti = new ConfettiGenerator(confettiSettings);
  confetti.render();
});
</script>

<style>
.confetti {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}
</style>

<template>
  <canvas class="confetti" ref="canvas"></canvas>
</template>
