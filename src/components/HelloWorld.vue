<template>
  <div class="hello">
    <!-- <div class="images"></div> -->
    <img :src="require(`@/assets/logo.png`)">
    <div>
      <p>{{titles}}</p>
      <p>{{msg}}</p>
      <button>++</button>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    titles: String,
    msg: String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.images{
  width: 300px;
  height: 200px;
  background: rgb(169, 169, 169);
}
.hello{
  display: flex;
  margin: 10px 0;
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
