<template>
  <div id="app">
    <Title msg="La mia prima app con VueCli"/>
    <img  src="./assets/deLorean.jpg" alt="De_Lorean">
  </div>
</template>

<script>

import Title from './components/Title.vue'

export default {
  name: 'App',
  components: {
    Title
    
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
img{
  height: 50%;
  width: 50%;
}
</style>
