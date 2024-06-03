<script setup lang="ts">
useHead({
  meta: [{ name: 'viewport', content: 'width=device-width, initial-scale=1' }],
  link: [{ rel: 'icon', href: '/favicon.ico' }],
  htmlAttrs: {
    lang: 'pl',
  },
});

useSeoMeta({
  ogImage:
    'https://ocieplamyzycie.pl/wp-content/uploads/2019/11/remont_mieszkania.jpg',
  twitterImage:
    'https://ocieplamyzycie.pl/wp-content/uploads/2019/11/remont_mieszkania.jpg',
  twitterCard: 'summary_large_image',
  ogUrl:
    'https://ocieplamyzycie.pl/wp-content/uploads/2019/11/remont_mieszkania.jpg',
  twitterTitle: 'Profesjonalne Usługi Remontowe | Michał Trejda',
  twitterDescription:
    'MKT Solid | Twoje zaufane źródło kompleksowych usług remontowych. Gwarantujemy jakość, solidność i terminowość. Skontaktuj się z nami już dziś!',
});
</script>

<template>
  <Header />

  <UMain>
    <NuxtPage />
  </UMain>

  <Footer />
  <UNotifications />
</template>
