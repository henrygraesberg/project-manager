<script setup lang="ts">
definePageMeta({
  middleware: ['auth'],
})
useSeoMeta({
  title: 'Outline - Proflie'
})
useHead({
  htmlAttrs: {
    lang: 'en'
  },
  link: [
    {
      rel: 'icon',
      type: 'image/x-icon',
      href: '/favicon.ico'
    }
  ]
})
</script>

<template>
  <h1>Profile</h1>
</template>