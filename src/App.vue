<script setup>
import ZaneGomes from './components/ZaneGomes.vue'
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import JSON from './components/JSON.vue';
</script>

<template>
  <header>
  </header>

  <main>
    <JSON />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.wrapper > * {
  margin-bottom: 20px;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>

