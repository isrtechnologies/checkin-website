<script setup lang="ts">
// No script needed for now
</script>

<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/privacy-policy">Privacy Policy</router-link>
    </nav>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #121212;
  color: #ffffff;
  min-height: 100vh;
  padding: 20px;
}

nav {
  margin-bottom: 20px;
}

nav a {
  color: #ffffff;
  text-decoration: none;
  margin-right: 20px;
  padding: 10px;
  border-radius: 4px;
  transition: background-color 0.3s;
}

nav a:hover {
  background-color: #333;
}

nav a.router-link-active {
  background-color: #555;
}
</style>
