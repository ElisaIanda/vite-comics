<script>
export default {
    data() {
        return {
        }
    },
    props: {
        img: String,
        text: String
    }
}
</script>

<template>
    <div class="card ">
        <div class="card-img">
            <img :src="img" class="card-img-top" :alt="text">
        </div>
        <div class="card-body">
            <h6 class="card-title">{{ text }}</h6>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variable" as *;

.card {
    width: calc(100%/6);
    padding: 15px;
    --bs-card-bg: transparent;
    color: white;
    --bs-card-border-color:transparent ;
}

.card-img {
    aspect-ratio: 2/3;
    margin-bottom: 15px;

    img {
        object-fit: cover;
        object-position: center;
        aspect-ratio: 2/3;
    }
}

.card-img, .card-img-top {
    /* border-top-left-radius: var(--bs-card-inner-border-radius); */
    /* border-top-right-radius: var(--bs-card-inner-border-radius); */
}
</style>