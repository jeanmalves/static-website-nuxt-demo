<template>
  <div class="body-wrap">
    <Header />
    <Nuxt />
  </div>
</template>
<script>
import { Header } from '@/components/Header';

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
