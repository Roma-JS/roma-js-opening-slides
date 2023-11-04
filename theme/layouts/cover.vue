<script setup>
import { ref, onMounted } from "vue";
import ConfettiGenerator from "confetti-js";

// declare a ref to hold the element reference
// the name must match template ref value
const canvas = ref(null);

onMounted(() => {
  const confettiSettings = { target: canvas.value };
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
  <div class="slidev-layout cover text-center">
    <div class="my-auto w-full">
      <slot />
    </div>
    <canvas class="confetti" ref="canvas"></canvas>
  </div>
</template>
