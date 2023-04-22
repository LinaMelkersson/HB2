<template>
  <div id="app">
    <nav>
      <router-link to="/">Hyr här</router-link> |
      <router-link to="/about">Om oss</router-link>
    </nav>
    <router-view/>
    <my-Footer></my-Footer>

  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-image: url(../src/assets/backgroundimgtegel.jpg) ;
  background-size: cover;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: rgba(0, 0, 0, 0.851);
}

nav a.router-link-exact-active {
  color: grey;
}


</style>
