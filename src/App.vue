<template>
  <div id="nav">
    <div class="logo">
      <img alt="Vue logo" src="./assets/logo.png">
    </div>
    <router-link to="/">Dashboard</router-link> |
    <router-link to="/investments">Инвестиции</router-link> |
    <router-link to="/credits">Кредиты</router-link>
  </div>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
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

#nav .logo {
  width: 50px;
  height: 50px;
}

#nav .logo img {
  width: 100%;
  height: 100%;
}
</style>
