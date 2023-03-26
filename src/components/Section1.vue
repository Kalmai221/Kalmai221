<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="section">
    <h3>What do I know?</h3>
  </div>
</template>

<style scoped>
 .section {
   border-color: #41B883;
   border-radius: 5px;
   text-align: center;
   margin: 0 20 0 20;
   border-style: solid;
   border-width: 3px;
 }
</style>
