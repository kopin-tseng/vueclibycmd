<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>

  <Carousel v-model="value" loop>
      <CarouselItem v-for="item in 10" :key="item">
          <div class="demo-carousel">{{item}}</div>
      </CarouselItem>
  </Carousel>

</template>

<script>
    export default {
        data () {
            return {
                value: 0
            }
        }
    }
</script>

<style>
.demo-carousel{
  margin: 10px;
  font-size: 50px;
  height: 100px;
  background: rgb(102, 232, 113);
}
</style>