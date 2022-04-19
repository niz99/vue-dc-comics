<template>
    <footer>
        <LinkFooterComp/>
        <img src="../assets/img/dc-logo-bg.png" alt="DC logo">
    </footer>
</template>

<script>
import LinkFooterComp from './LinkFooterComp.vue'

export default {
  name: 'FooterComp',
  components: { 
      LinkFooterComp 
    }
}

</script>

<style scoped lang="scss">

    footer {
        display: flex;
        justify-content: space-around;
        padding-top: 1rem;
        background-image: url('../assets/img/footer-bg.jpg');
    }
    img {
        margin: -5%;
        height: 20rem;
    }

</style>