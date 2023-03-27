<script>
import TheHeader from './components/TheHeader.vue';
import BlueBanner from './components/BlueBanner.vue';
import TheFooter from './components/TheFooter.vue';
import TheDownFooter from './components/TheDownFooter.vue'


export default {

  components: {
    TheHeader,
    BlueBanner,
    TheFooter,
    TheDownFooter
  }
}
</script>

<template>
  <TheHeader />
  <main>
    >>> Content goes here ---
  </main>
  <BlueBanner />
  <TheFooter />
  <TheDownFooter />
</template>

<style>
main {
  background: black;
  height: 100px;
  color: white;
}
</style>
