<template>
    <div>
        <div class="icon-list"> <img src="../assets/img/buy-comics-digital-comics.png" alt=""> digital comics</div>
        <div class="icon-list"> <img src="../assets/img/buy-comics-merchandise.png" alt=""> dc merchandise</div>
        <div class="icon-list"> <img src="../assets/img/buy-comics-subscriptions.png" alt=""> subscription</div>
        <div class="icon-list"> <img src="../assets/img/buy-comics-shop-locator.png" alt=""> comic shop locator</div>
        <div class="icon-list"> <img src="../assets/img/buy-dc-power-visa.svg" alt=""> dc power visa</div>
    </div>
</template>

<script>

export default {
  name: 'IconComp'
}

</script>

<style scoped lang="scss">

    div {
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: #0d6af9;
    }
    .icon-list {
        align-self: center;
        text-transform: uppercase;
        padding: 3rem;
        color: white;
    }

    img {
        height: 30px;
        margin-right: 10px;
    }


</style>
