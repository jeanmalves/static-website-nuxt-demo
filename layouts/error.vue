<template>
  <main>
    <section class="hero">
      <div class="container">
        <div class="hero-inner">
          <div class="hero-copy">
            <h1 class="hero-title mt-0">OPS Page Not Found</h1>
            <p class="hero-paragraph">
              This page isn't available.
            </p>
            <div class="hero-cta">
              <NuxtLink class="button button-primary" to="/">
                Go to Home Page
              </NuxtLink>
            </div>
          </div>
          <div class="hero-figure anime-element">
            <svg
              class="placeholder"
              width="528"
              height="396"
              viewBox="0 0 528 396"
            >
              <rect width="528" height="396" style="fill: transparent" />
            </svg>
            <div
              class="hero-figure-box hero-figure-box-01"
              data-rotation="45deg"
            ></div>
            <div
              class="hero-figure-box hero-figure-box-02"
              data-rotation="-45deg"
            ></div>
            <div
              class="hero-figure-box hero-figure-box-03"
              data-rotation="0deg"
            ></div>
            <div
              class="hero-figure-box hero-figure-box-04"
              data-rotation="-135deg"
            ></div>
            <div class="hero-figure-box hero-figure-box-05"></div>
            <div class="hero-figure-box hero-figure-box-06"></div>
            <div class="hero-figure-box hero-figure-box-07"></div>
            <div
              class="hero-figure-box hero-figure-box-08"
              data-rotation="-22deg"
            ></div>
            <div
              class="hero-figure-box hero-figure-box-09"
              data-rotation="-52deg"
            ></div>
            <div
              class="hero-figure-box hero-figure-box-10"
              data-rotation="-50deg"
            ></div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  head() {
    return {
      bodyAttrs: {
        class: "is-boxed has-animations",
      },
    };
  },
  props: ["error"],
};
</script>