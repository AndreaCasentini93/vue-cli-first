<template>
  <div id="app">
    <Hero/>
  </div>
</template>

<script>
import Hero from './components/Hero';

export default {
  name: 'App',
  components: {
    Hero
  }
}
</script>

<style lang="scss">
  * {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }
</style>
