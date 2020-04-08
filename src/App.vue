<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/tiger-1391526.jpg">

    <h1>Welcome to The Animal Rescue Club</h1>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
body {
  background-image: url("./assets/repeating-tigers.jpg");
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  border-radius: 5px;
  margin: 20px 15% 20px 15%;
  padding: 20px;
  width: auto;
  height: 100%;
  background-color: white;
}

#app img {
  width: 50em;
  height: 50em;
  border-radius: 5px;
}

</style>
