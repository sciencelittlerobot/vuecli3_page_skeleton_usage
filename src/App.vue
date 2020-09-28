<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">home</router-link>
      <router-link to="/about">about</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
body::-webkit-scrollbar {
  width: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
}
#nav {
  padding: 30px;

  a{
      font-weight: bold;
      color: #2c3e50;
      text-decoration: none;
      width: 200px;
      height: 40px;
      line-height: 40px;
      display: inline-block;
      background: #dddddd;
      margin: 0 5px;

      &.router-link-exact-active {
        color: #42b983;
      }
  }
}
</style>
