<template>
  <div class="container">
      <div class="logo">
      <img alt="Vue logo" src="../assets/logo.png">
    </div>
    <div class="nav">
      <a href="">Общее</a>
      <a href="">Инвестиции</a>
      <a href="">Кредиты</a>
      <a href="">Свободные средства</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.container {
  max-width: 1440px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 0 auto;
  padding: 5px 20px;
  background: #e5e5e5;
}

.logo {
  width: 50px;
  height: 50px;
}

.logo img {
  width: 100%;
  height: 100%;
}

.nav {

}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
  padding: 0 10px;
}
a:hover {
  color: black;
}
</style>
