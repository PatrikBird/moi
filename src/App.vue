<script setup lang="ts">
useHead({
  title: 'Moi',
  meta: [
    { name: 'description', content: 'Opinionated Vite Starter Template' },
    {
      name: 'theme-color',
      content: computed(() => isDark.value ? '#00aba9' : '#ffffff'),
    },
  ],
  // link: [
  //   {
  //     rel: 'icon',
  //     type: 'image/svg+xml',
  //     href: computed(() => preferredDark.value ? '/favicon-dark.svg' : '/favicon.svg'),
  //   },
  // ],
})
</script>

<template>
  <TheNavbar />
  <RouterView />
</template>
