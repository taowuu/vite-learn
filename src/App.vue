<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <h1 class="name">tao</h1>
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
</template>

<script lang="ts">
import HelloWorld from '/@/components/HelloWorld.vue'
const name:string = 'tao'
import '/@/assets/app.css'
import data from './assets/app.json'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  mounted(){
    console.log(name)
    console.log(data)
  }
}
</script>

<style lang="scss">
  .name{
    color:green;
  }
</style>