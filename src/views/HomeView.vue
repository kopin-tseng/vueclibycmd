<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld titles='hihif' msg="Welcome to Your Vue.js App"/>
    <HelloWorld titles='gg' msg="see ya"/>
    <HelloWorld titles='ewf;nejw' msg="fff"/>
    
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
