<template>
  <div id="app">
    <Title/>
  </div>
</template>

<script>
import Title from './components/Title';

export default {
  name: 'App',
  components: {
    Title
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
