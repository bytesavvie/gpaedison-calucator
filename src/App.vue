<template>
  <div id="app">
       <router-view />
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Courier+Prime&family=IBM+Plex+Sans+Thai+Looped&family=Mukta&family=Roboto&display=swap');
body { 
   background: powderblue;
   font-family: 'IBM Plex Sans Thai Looped', sans-serif;
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
