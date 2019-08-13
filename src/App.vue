<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
@import "/src/styles";

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  font-size: 1em;
  line-height: 1.5;
  display: flex;
  min-height: 100vh;
  flex-direction: column;
}
body {
  background: #ee5050;
}
/* #nav {
  padding: 30px;
} */

/* #nav a {
  font-weight: bold;
  color: #2c3e50;
} */

/* #nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
