<template>
  <header class="site-header">
    <div class="container">
      <div class="site-header-inner">
        <div class="brand header-brand">
          <h1 class="m-0">
            <NuxtLink to="/">
              <Logo />
            </NuxtLink>
          </h1>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
import { Logo } from '@/components/Logo';
export default {};
</script>