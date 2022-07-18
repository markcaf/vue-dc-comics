<template>
  <section class="py-4">
    <nav class="d-flex justify-content-center gap-5">
        <ul class="list-unstyled">
            <li>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="Buy Comics">
            </li>
            <li>
                DIGITAL COMICS
            </li>
        </ul>

        <ul class="list-unstyled">
            <li>
                <img src="../assets/img/buy-comics-merchandise.png" alt="Buy Comics">
            </li>
            <li>
                DC MERCHANDISE
            </li>
        </ul>

        <ul class="list-unstyled">
            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="Buy Comics">
            </li>
            <li>
                SUBSCRIPTION
            </li>
        </ul>

        <ul class="list-unstyled">
            <li>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="Buy Comics">
            </li>
            <li>
                COMIC SHOP LOCATOR
            </li>
        </ul>

        <ul class="list-unstyled">
            <li>
                <img class="svg-icon" src="../assets/img/buy-dc-power-visa.svg" alt="Buy Comics">
            </li>
            <li>
                DC POWER VISA
            </li>
        </ul>
    </nav>
  </section>
</template>

<script>
export default {
    name: "MarketDC",
}
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

section{
    background-color: $brandColor;

    ul{
        li{
            display: inline-block;
            margin-right: 1rem;
            color: white;
            font-size: 13px;

            img{
                height: 50px;

                &.svg-icon{
                    width: 50px;
                }
            };
        }

    }
}

</style>