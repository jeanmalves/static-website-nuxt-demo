<template>
  <div class="body-wrap">
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>
<script>
import { Header } from '@/components/Header';
import { Footer } from '@/components/Footer';

export default {
  head() {
    return {
      bodyAttrs: {
        class: "is-boxed has-animations",
      },
    };
  },
};
</script>
