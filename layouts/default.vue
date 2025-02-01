<script setup>
import Footer from '~/components/global/Footer.vue';
useHead({
  htmlAttrs: {
    lang: 'en',
  },
  meta: [
    { property: 'og:title', content: `PaxDefender` },
    { name: 'description', content: 'PaxDefender is a travel agency landing page built with Nuxt 3 and TailwindCSS.' },
    { property: 'og:description', content: 'PaxDefender is a travel agency landing page built with Nuxt 3 and TailwindCSS.' },
    { property: 'og:url', content: 'https://paxdefender-ke.vercel.app/' },
    { name: 'twitter:title', content: 'PaxDefender' },
    { name: 'twitter:description', content: 'PaxDefender is a travel agency landing page built with Nuxt 3 and TailwindCSS.' },
    { name: 'twitter:site', content: 'https://paxdefender-ke.vercel.app/' }
  ],
  title: `PaxDefender`,
})
</script>

<template>
  <main class="max-w-8xl">
    <slot/>
    <Footer />
  </main>
</template>
