<script>
export default {
    name: "FooterComponent",
    data() {
        return {

        }
    },
    methods: {

    }
}
</script>

<template>
    <footer>
        <div class="footer-img">
            <div class="container">
                <div class="link-footer-left">
                    <ul>
                        <h3>
                            DC COMICS
                        </h3>
                        <li>
                            <a href="">Characters</a>
                        </li>
                        <li>
                            <a href="">Comics</a>
                        </li>
                        <li>
                            <a href="">Movies</a>
                        </li>
                        <li>
                            <a href="">TV</a>
                        </li>
                        <li>
                            <a href="">Games</a>
                        </li>
                        <li>
                            <a href="">Videos</a>
                        </li>
                        <li>
                            <a href="">News</a>
                        </li>
                    </ul>
                    <ul>
                        <h3>
                            SHOP
                        </h3>
                        <li>
                            <a href="">Shop DC</a>
                        </li>
                        <li>
                            <a href="">Shop DC collectbiles</a>
                        </li>
                    </ul>
                </div>
                <div class="link-footer-center">
                    <ul>
                        <h3>
                            DC
                        </h3>
                        <li>
                            <a href="">Terms Of Use</a>
                        </li>
                        <li>
                            <a href="">Privacy policy (New)</a>
                        </li>
                        <li>
                            <a href="">Ad Choises</a>
                        </li>
                        <li>
                            <a href="">Advertising</a>
                        </li>
                        <li>
                            <a href="">Jobs</a>
                        </li>
                        <li>
                            <a href="">Subscriptions</a>
                        </li>
                        <li>
                            <a href="">Talent Workshops</a>
                        </li>
                        <li>
                            <a href="">CPSC Certificates</a>
                        </li>
                        <li>
                            <a href="">Ratings</a>
                        </li>
                        <li>
                            <a href="">Shop Help</a>
                        </li>
                        <li>
                            <a href="">Contac Us</a>
                        </li>
                    </ul>
                </div>
                <div class="link-footer-right">
                    <ul>
                        <h3>
                            SITES
                        </h3>
                        <li>
                            <a href="">DC</a>
                        </li>
                        <li>
                            <a href="">MAD Magazine</a>
                        </li>
                        <li>
                            <a href="">DC kids</a>
                        </li>
                        <li>
                            <a href="">DC Universe</a>
                        </li>
                        <li>
                            <a href="">DC Power Visa</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="footer-button">
            <div class="container">
                <div class="my-row">
                    <div class="my-col-button">
                        <button>
                            SIGN-UP NOW!
                        </button>
                    </div>
                    <div class="my-col-link">
                        <h3>
                            FOLLOW US
                        </h3>
                        <ul>
                            <li>
                                <a href=""><img src="../assets/img/footer-facebook.png" alt="Facebook"></a>
                            </li>
                            <li>
                                <a href=""><img src="../assets/img/footer-periscope.png" alt="Facebook"></a>
                            </li>
                            <li>
                                <a href=""><img src="../assets/img/footer-pinterest.png" alt="Facebook"></a>
                            </li>
                            <li>
                                <a href=""><img src="../assets/img/footer-twitter.png" alt="Facebook"></a>
                            </li>
                            <li>
                                <a href=""><img src="../assets/img/footer-youtube.png" alt="Facebook"></a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use "../assets/scss/footer.scss" as *;
@use "../assets/scss/partials/variables.scss" as *;
@use "../assets/scss/partials/mixins.scss" as *;

.footer-img {
    .container {
        position: relative;
    }
    .container::after {
        content: '';
        background-image: url(../assets/img/dc-logo-bg.png);
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
        display: block;
        width: 40%;
        height: $height-percentual;
        position: absolute;
        top: 0;
        right: 0;
    }
}
.footer-button {

    ul {
        @include flex;
    }
    li {
        padding: 0 5px;
    }
    h3 {
        color: $bg-links-color;
        padding-right: 10px;
    }
}
</style>