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
    <h2>What do I know?</h2>
    <br>
    <div class="insection">
      <h3>Website Development</h3>
      <p>You can review the source code of this website at <a href="https://github.com/kalmai221/Kalmai221">Github</a> if you don't trust
      me</p>
    </div>
    <br>
    <div class="insection">
      <h3>Discord Bot Development</h3>
      <p>If you wish to view the bot in action, contact me on Discord at <b>Kalmai221#1905</b> and I can schedule a time for you to test the bot</p>
    </div>
  </div>
</template>

<style scoped>
 .section {
   border-color: #41B883;
   border-radius: 5px;
   text-align: center;
   margin: 0 20 0 20;
   border-style: solid;
   border-width: 1px;
 }
 
 .insection {
   border-color: #41B883;
   border-radius: 5px;
   text-align: center;
   margin: 0 10 0 10;
   border-style: solid;
   border-width: 1px;
 }
</style>
