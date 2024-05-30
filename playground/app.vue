<script setup lang="ts">
import { VueDraggable } from 'vue-draggable-plus'

const items = [[{
  label: 'test',
}]]
</script>

<template>
  <UContainer class="min-h-screen flex items-center">
    <UDropdown :items="items" />
  </UContainer>
</template>

<style>
body {
  @apply antialiased font-sans text-gray-700 dark:text-gray-200 bg-white dark:bg-gray-900;
}
</style>
