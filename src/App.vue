<script>
import TheHeader from './components/TheHeader.vue';
import BlueBanner from './components/BlueBanner.vue'


export default {

  components: {
    TheHeader,
    BlueBanner
  }
}
</script>

<template>
  <TheHeader />
  <main>
    >>> Content goes here ---
  </main>
  <BlueBanner />
</template>

<style>
main {
  background: black;
  height: 100px;
  color: white;
}
</style>
