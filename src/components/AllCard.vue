<script>
import "./Card.vue"
import singleCard from './Card.vue'
import array from "../db/dc-comics"

export default {
    data() {
        return {
            array,
        }
    },
    components: {
        singleCard,
    },
    methods: {
        Image(img) {
            return new URL(img, import.meta.url).href;
        }

    }
}
</script>

<template>
    <div class="container">
        <div class="d-flex flex-wrap">

            <singleCard v-for="(film, index) in array" :key="index" :img="Image(film.thumb)" :text="film.series" />
        </div>
    </div>
</template>


<style lang="scss" scoped>
@use "../styles/partials/variable" as *;


.container {
    min-height: 400px;
    padding-top: 60px;
    color: white;
}
</style>