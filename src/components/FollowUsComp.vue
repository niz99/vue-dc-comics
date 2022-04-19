<template>
    <div>
        <h3>follow us</h3>
        <img src="../assets/img/footer-facebook.png" alt="Facebook logo">
        <img src="../assets/img/footer-twitter.png" alt="Twitter logo">
        <img src="../assets/img/footer-youtube.png" alt="Youtube logo">
        <img src="../assets/img/footer-pinterest.png" alt="Pinterest logo">
        <img src="../assets/img/footer-periscope.png" alt="Periscope logo">
    </div>
</template>

<script>

export default {
  name: 'FollowUsComp'
}

</script>

<style scoped lang="scss">

    div {
        display: flex;
        align-items: center;
    }
    h3 {
        text-transform: uppercase;
        color: #0d6af9;
        margin-right: 15px;
    }
    img {
        height: 25px;
        margin: 10px;
    }

</style>