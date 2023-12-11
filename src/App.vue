<script setup lang="ts">
const route = useRoute()

useHead({
  title: () => route.meta.title || 'Proton Corse 🏎️',
  meta: [
    {
      property: 'og:title',
      content: () => route.meta.title,
    },
    {
      name: 'twitter:title',
      content: () => route.meta.title,
    },
  ],
})
</script>
<template>
  <main>
    <router-view></router-view>
  </main>

</template>
