<script>
export default {
    name: "HeaderComponent",
    data() {
        return {

        }
    },
    methods: {

    }
}
</script>

<template>
    <header>
        <div class="container">
            <div class="my-row">
                <div class="my-col">
                    <img src="../assets/img/dc-logo.png" alt="LOGO DC">
                </div>
                <div class="my-col-link">
                    <ul>
                        <li>
                            <a href="#">CHARACTERS</a>
                        </li>
                        <li>
                            <a href="#">COMICS</a>
                        </li>
                        <li>
                            <a href="#">MOVIES</a>
                        </li>
                        <li>
                            <a href="#">TV</a>
                        </li>
                        <li>
                            <a href="#">GAMES</a>
                        </li>
                        <li>
                            <a href="#">COLLECTIBLES</a>
                        </li>
                        <li>
                            <a href="#">VIDEO</a>
                        </li>
                        <li>
                            <a href="#">FANS</a>
                        </li>
                        <li>
                            <a href="#">NEWS</a>
                        </li>
                        <li>
                            <a href="#">SHOP</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;
@use "../assets/scss/header.scss" as *;
img {
    width: 80px;
    height: 80px;
}
</style>