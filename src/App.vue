<template>
  <div id="app">
    <div id="nav">
      <v-toolbar class="green white-text">
      <router-link to="/">Home</router-link> 
      <v-spacer></v-spacer>
      <router-link to="/about">About</router-link>
      </v-toolbar>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  background-color: cornflowerblue;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
