<template>
    <footer>
        <div class="footer-links">
            <div class="container d-flex justify-content-between">
                <div class="links mt-5 d-flex flex-wrap">

                    <div class="menu">
                        <h5>DC COMICS</h5>
                        <ul class="list-unstyled">
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                        </ul>

                        <h5>SHOP</h5>
                        <ul class="list-unstyled">
                            <li>Characters</li>
                            <li>Characters</li>
                        </ul>
                    </div>

                    <div class="menu">
                        <h5>DC</h5>
                        <ul class="list-unstyled">
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                        </ul>
                    </div>

                    <div class="menu">
                        <h5>SITES</h5>
                        <ul class="list-unstyled">
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                        </ul>
                    </div>

                </div>

                <div class="logo-bg">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>

        <div class="footer-social py-5">
            <div class="container d-flex justify-content-between">
                
                <div class="cta-button text-white">
                    SIGN-UP NOW!
                </div>

                <div class="social d-flex align-items-center gap-3">
                    <div>FOLLOW US</div>
                    <img src="../assets/img/footer-facebook.png" alt="facebook Logo">
                    <img src="../assets/img/footer-periscope.png" alt="periscope Logo">
                    <img src="../assets/img/footer-pinterest.png" alt="pinterest Logo">
                    <img src="../assets/img/footer-twitter.png" alt="twitter Logo">
                    <img src="../assets/img/footer-youtube.png" alt="youtube Logo">
                </div>

            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "Footer",
}
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

    footer{
        .footer-links{
        background-image: url(../assets/img/footer-bg.jpg);
        background-size: cover;
        height: 350px;
        overflow: hidden;
        color: white;

            .menu{
                margin-right: 2.5rem;

                h5{
                color: white;
                font-stretch: extra-condensed;
                font-weight: bold;
                }

                li{
                color: #939393;
                font-size: 14px;
                }
            }
        }

        .footer-social{
            background-color: #303030;

            .cta-button{
            padding: 10px;
            border: $brandColor solid 2px;
            }

            .social {
            color: $brandColor;
            font-weight: bold;
            }

        }
    }

    .logo-bg{
        img{
            height: 500px;
            position: relative;
            bottom: 80px;
        }
    }
</style>