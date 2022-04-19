<template>
    <footer>
        <button>sign-up now!</button>
        <FollowUsComp/>
    </footer>
</template>

<script>

import FollowUsComp from './FollowUsComp.vue'

export default {
  name: 'SignupComp',
  components: { 
      FollowUsComp 
    }
}

</script>

<style scoped lang="scss">

    footer {
        background-color: #303030;
        display: flex;
        justify-content: space-around;
        padding: 25px;
    }
    button {
        text-transform: uppercase;
        background-color: transparent;
        color: white;
        border: 2px solid #0d6af9;
        padding: 10px 30px;
        font-weight: 500;
    }

</style>