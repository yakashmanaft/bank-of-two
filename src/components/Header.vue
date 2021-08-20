<template>
  <div class="container">
      <div class="logo">
      <img alt="Vue logo" src="../assets/logo.png">
    </div>
    <div class="nav">
      <a href="">Общие сведения</a>
      <a href="">Разделы</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
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
  padding: 0 20px;
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
}
</style>
