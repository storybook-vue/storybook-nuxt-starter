<template>
  <div>
    Home
  </div>
  <div>
    {{ msg }}
  </div>
</template>
<script setup>
defineProps({
  msg: String,
})
</script>