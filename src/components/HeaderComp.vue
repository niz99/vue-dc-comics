<template>
    <header>
        <img src="../assets/img/dc-logo.png" alt="">
        <VociHeaderComp/>
    </header>
</template>

<script>

import VociHeaderComp from './VociHeaderComp.vue'

export default {
  name: 'HeaderComp',
  components: {
    VociHeaderComp
  }
}
</script>

<style scoped lang="scss">

header{
    display: flex;
    justify-content: space-around;
    align-items: center;
}

img{
    height: 80px;
    margin: 0;
}

</style>
