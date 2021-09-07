<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Demo from '@/components/Demo.vue'
</script>

<template>
  <demo />
</template>

<style>
  /*! @import */
  @tailwind base;
  @tailwind components;
  @tailwind utilities;

  body {
    display: flex;
    justify-content: center;
    align-items: center;

    min-height: 100vh;
  }
</style>
