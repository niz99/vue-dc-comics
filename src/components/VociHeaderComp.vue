<template>
    <nav>
        <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">Tv</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Collectibles</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">Fans</a></li>
            <li><a href="#">News</a></li>
            <li><a href="#">Shop</a></li>
        </ul>
    </nav>
  
</template>

<script>
export default {
  name: 'VociHeaderComp'
}
</script>

<style scoped lang="scss">

    ul{
        display: flex;
        align-items: center;

        li{
            list-style: none;
            padding: 10px;
            color: black;
            text-transform: uppercase;
            font-weight: bold;
            font-size: 0.9rem;
        }
    }

    a{
        text-decoration: none;
        color: black;
        
        &:hover{
            color: #0d6af9;
            border-bottom: 2px inset #0d6af9;
            padding-bottom: 10px;
        }
    }

</style>