<template>
  <div>
    <svg-icon icon-class="question" @click="goto" />
  </div>
</template>

<script setup>
const url = ref('http://doc.ai-interview.vip/ai-interview-vue');

function goto() {
  window.open(url.value)
}
</script>