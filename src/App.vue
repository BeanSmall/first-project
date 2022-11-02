<template>
  <div id="root">
    app组件
    <Home></Home>
    <About></About>
  </div>
</template>

<script>
import Home from './components/Home.vue'
import About from './components/About.vue'

export default {
  name: 'App',
  components: {
      Home:Home,
      About:About
  }
}
</script>

<style>
#root {
  color: red;
  font-size: 50px;
}
</style>
