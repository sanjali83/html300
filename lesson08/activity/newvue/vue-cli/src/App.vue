<template>
  <div id="app">
    <app-header heading = "Welcome to VUE Components"></app-header>

    <blog-post title = "hello"></blog-post>
    <blog-post title = "Welcome to"></blog-post>
    <blog-post title = "Bellevue"></blog-post>

    <router-view></router-view>
    <router-link to = "/other"> Other </router-link>
    <router-link to = "/next"> Next </router-link>

    <div>
        <button-counter></button-counter>
        <button-counter></button-counter>
        <button-counter></button-counter>
    </div>

  </div>

</template>

<script>
export default {
  name: 'app',
  data () {
    return {
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
app-header{

}
h1, h2 {
  font-weight: normal;
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
