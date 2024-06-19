<template>
  <nav className="p-[10px] flex justify-between bg-slate-900 text-white">
    <div className="w-[35px] h-[35px] ">
      <img src="./assets/logo.png" alt="logo" />
    </div>
    <div class="space-x-4 text-white">
      <router-link to="/">Home</router-link>
      <router-link to="/news">news</router-link>
      <router-link to="/content">content</router-link>
      <router-link to="/about">About</router-link>
    </div>
    <div className="space-x-4 pr-[50px] text-white">
      <router-link to="/login">Login</router-link>
      <router-link to="/signup">Signup</router-link>
    </div>
  </nav>
  <router-view />
</template>
<!-- 
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  background-color: black;
  
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style> -->
