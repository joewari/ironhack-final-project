<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
  </div>
</template>
<style scoped>
* {
  color: rgb(238, 78, 4);
  margin-bottom: 1em;
  text-align: center;
}
</style>
