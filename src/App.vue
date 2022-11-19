<template>
  <header>
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/news">News</router-link> |
      <router-link to="/product">Product</router-link>
    </nav>
  </header>
  <router-view/>
  <footer>
    footer
  </footer>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #784bff;
    }
  }
}
img{
  width: 5rem;
  aspect-ratio: 1/1;
}
header{
  height: 100px;
  background-color: rgb(255, 202, 43);
}
footer{
  height: 200px;
  background-color: rgb(180, 44, 44);
}
</style>
