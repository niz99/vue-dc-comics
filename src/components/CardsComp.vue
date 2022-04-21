<template>
    <div class="card">
        <div class="series">
            <img class="thumb" :src="thumb" alt="">
        </div>
        <span> {{series}} </span>
    </div>
</template>

<script>
export default {
    name: 'CardsComp',
    props: {
        thumb: String,
        series: String
    }
}
</script>

<style scoped lang="scss">
.series {
        height: 100%;
        margin-bottom: 15px;
    }
    .card {
        height: 200px;
        width: 200px;
        margin: 10px 0 40px 0;
    }
    img {
        clip-path: inset(0 0 33% 0);
    }
    span {
        color: white;
        text-transform: uppercase;
        display: inline-block;
        width: 100%;
        text-align: left;
    }
</style>