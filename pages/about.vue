<template>
  <div>
    About
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