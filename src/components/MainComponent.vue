<script>
import BlueLinksComponent from "./BlueLinksComponent.vue"
export default {
    components: {
        BlueLinksComponent
    },
    name: "MainComponent",
    data() {
        return {

        }
    },
    methods: {

    }
}
</script>

<template>
    <main>
        <div class="container">
            <div class="content">
                <p>
                --<i class="fa-solid fa-angle-right"></i> Content goes here <i class="fa-solid fa-angle-left"></i>--
                </p>
            </div>
        </div>
    </main>
    <BlueLinksComponent />
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;
@use "../assets/scss/main.scss" as *;
</style>