<template>
  <div class="about">
    <h1>This is an news page</h1>
    <Button type="primary">Primary</Button>
    <Button type="warning">Warning</Button>
    <HelloWorld titles='ewf;nejw' msg="fff"/>
    <images link="https://fakeimg.pl/300x200/200" />
    
  </div>
</template>

<script>
// @ is an alias to /src

import HelloWorld from '@/components/HelloWorld.vue'
import images from '@/components/images.vue'

export default {
  name: 'NewsView',
  components: {
    HelloWorld,
    images,
  }
}
</script>