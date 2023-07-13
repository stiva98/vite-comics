<script>
export default {
    name: "BlueLinksComponent",
    data() {
        return {

        }
    },
    methods: {

    }
}
</script>

<template>
    <section>
        <div class="container">
            <ul>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="DIGITAL COMICS">
                    <a href="">DIGITAL COMICS</a>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="DC MERCHANDISE">
                    <a href="">DC MERCHANDISE</a>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="SUBSCRIPTION">
                    <a href="">SUBSCRIPTION</a>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="COMIC SHOP LOCATOR">
                    <a href="">COMIC SHOP LOCATOR</a>
                </li>
                <li>
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="DC POWER VISA">
                    <a href="">DC POWER VISA</a>
                </li>
            </ul>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use "../assets/scss/bluelinks.scss" as *;
@use "../assets/scss/partials/variables.scss" as *;
img {
    width: 30px;
    height: 40px;
}
</style>