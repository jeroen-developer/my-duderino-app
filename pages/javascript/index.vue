<script setup>
definePageMeta({
  layout: "blog-post",
});
</script>
<template>
  <h1>This is the javascript index page the .vue one</h1>
  <button @click="navigateTo('/javascript/hello')">to blog</button>
</template>
