<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/day">Picture of the Day</router-link>
      <router-link to="/month">Pictures of the Month</router-link>
    </div>
    <router-view />
  </div>
</template>



<style>
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 10px;
  background: black;
  color: white;
  display: flex;
  justify-content: space-around;
}

#nav a {
  font-weight: bold;
  color: white;
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #6295e2;
}
</style>
