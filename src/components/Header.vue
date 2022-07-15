<template>
    <header class="container">
        <nav class="d-flex justify-content-between align-items-center py-3">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="DC Universe Logo">
            </div>

            <ul class="list-unstyled">
                <li>Characters</li>
                <li class="active_link">Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Collectibles</li>
                <li>Videos</li>
                <li>Fans</li>
                <li>News</li>
                <li>Shop</li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

    ul{
        margin: 0;

        li{
            display: inline-block;
            padding: 1rem;
            text-transform: uppercase;
            font-weight: bold;
            font-size: 14px;
            color: #534f49;
            font-stretch: extra-condensed;

            &.active_link{
                color: $brandColor;
            }
        }
    }
</style>