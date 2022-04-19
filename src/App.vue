<template>
  <div id="app">
    <HeaderComp/>
    <ContentComp/>
    <IconComp/>
    <FooterComp/>
    <SignupComp/>
  </div>
</template>

<script>

import HeaderComp from './components/HeaderComp.vue'
import ContentComp from './components/ContentComp.vue'
import IconComp from './components/IconComp.vue'
import FooterComp from './components/FooterComp.vue'
import SignupComp from './components/SignupComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    ContentComp,
    IconComp,
    FooterComp,
    SignupComp
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
