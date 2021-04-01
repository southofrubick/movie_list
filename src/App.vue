<template>
  <div id="nav">
    <router-link to="/">Home</router-link>
    <router-link to="/addMovie">Add Movie</router-link>
    <router-link to="/movieList">Movie List</router-link>
  </div>
  <router-view />
</template>

<style>
body{
  margin: 0;
  background-color: rgb(100, 140, 240);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 10px;
  padding-top: 40px;
  width: 100vw;
  background: linear-gradient(rgb(75, 100, 170) 0%, rgb(100, 130, 200) 27.5%, 
  rgb(100, 130, 200) 67.5%, rgb(75, 100, 170) 95%, rgb(255,255,255) 98%);
  font-size: 2vw
}

#nav a {
  padding: 50px;
  font-weight: bold;
  color: whitesmoke;
  text-shadow: 4px 2px 1px red;
}

#nav a.router-link-exact-active {
  color: red;
  text-shadow: 4px 2px 1px whitesmoke;
}
</style>
