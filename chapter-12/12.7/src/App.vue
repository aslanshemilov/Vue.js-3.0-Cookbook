<template>
  <div id="app">
    <img
      v-if="display"
      alt="Vue logo" src="./assets/logo.png">
    <button
      @click="display = !display"
    >
      Toggle
    </button>
  </div>
</template>

<script>
export default {
  name: 'App',
  data: () => ({
    display: true,
  }),
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
