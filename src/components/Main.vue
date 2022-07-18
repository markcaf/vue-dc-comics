<template>
    <main>
        <div class="container">
            <div class="row">
                <div class="col-2 heading text-center py-2">
                    Current Series
                </div>
            </div>

            <div class="row flex-column">
                <div class="col-12 text-white py-5 fs-3">
                    --> Content goes here
                </div>
            </div>
        </div>

    </main>
  
</template>

<script>
export default {
    name: "Main",
}
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

    main{
        background-color: black;
        position: relative;

        .heading{
            color: white;
            background-color: $brandColor;
            font-size: 20px;
            text-transform: uppercase;
            font-weight: bold;
            font-stretch: ultra-condensed;
            position: absolute;
            top: -25px;
        }
    }

</style>