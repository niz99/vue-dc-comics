<template>
  <div id="app">
    <HeaderComp/>
    <ContentComp/>
  </div>
</template>

<script>
import ContentComp from './components/ContentComp.vue'
import HeaderComp from './components/HeaderComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    ContentComp
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
