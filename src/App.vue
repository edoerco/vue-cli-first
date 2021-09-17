<template>
  <div>
    <Title />
    <jumbotron />
  </div>

</template>

<script>
import jumbotron from './components/jumbotron.vue'
import Title from './components/Title.vue'


export default {
  name: 'App',
  components: {
    jumbotron,
    Title
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
