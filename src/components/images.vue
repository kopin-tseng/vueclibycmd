<template>
    <div class="hello">
        <img :src="link" alt="">
    </div>
  </template>

<script>
export default {
  props: {
    link: String
  }
}
</script>
<style lang="scss">
img{
//   background-image: url("https://picsum.photos/300/200/?random=10");
  width: 300px;
  aspect-ratio: 1/1;
}
</style>