<script setup>
import Box from "./components/BoxImg.vue";

</script>

<template>
  
  <div class="row">
    <div v-for="n in 6" :key="n" class="col-4">
    {{ n }}
      <Box></Box>
    </div>
  </div>

</template>

<style scoped>
 
</style>
