<script>
export default {
    name: "FilmComponent",
    data() {
        return {

        }
    },
    props: {
        filmImage: String,
        filmTitle: String
    }
}
</script>
<template>
    <div class="card">
        <img :src="filmImage" :alt="filmTitle">
        <h3>
            {{ filmTitle }}
        </h3>
    </div>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;
@use "../assets/scss/film.scss" as *;
</style>