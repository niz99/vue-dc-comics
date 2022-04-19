<template>
    <div>
        <div class="col">
            <h3>dc comics</h3>

            <ul>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul>

            <h3>dc shop</h3>

            <ul>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
            </ul>
        </div>

        <div class="col">
            <h3>dc</h3>

            <ul>
                <li>terms of use</li>
                <li>privacy policy (new)</li>
                <li>ad choices</li>
                <li>advertising</li>
                <li>jobs</li>
                <li>subscriptions</li>
                <li>talent workshops</li>
                <li>CPSC certificates</li>
                <li>ratings</li>
                <li>shop help</li>
                <li>contact us</li>
            </ul>

        </div>

        <div class="col">
            <h3>sites</h3>

            <ul>
                <li>DC</li>
                <li>MAD magazine</li>
                <li>DC kids</li>
                <li>DC universe</li>
                <li>DC power visa</li>
            </ul>

        </div>
    </div>
</template>

<script>

export default {
  name: 'LinkFooterComp'
}

</script>

<style scoped lang="scss">

    div {
        display: flex;
        margin: 10px;
    }
    .col {
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        padding: 0;
        margin-right: 20px;
    }
    h3 {
        color: white;
        text-transform: uppercase;
        margin: 0;
    }
    ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
        display: flex;
        flex-direction: column;
        margin-bottom: 25px;
    }
    li {
        margin: 0;
        color: rgb(184, 179, 179);
        align-self: flex-start;
        text-transform: capitalize;
    }

</style>