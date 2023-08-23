
<script>
export default {
    data() {
        return {
            bannerItems: [
                {
                    title: 'DIGITAL COMICS',
                    image: '../assets/img/buy-comics-digital-comics.png',
                    alt: 'digital comics img'
                },
                {
                    title: 'DC MERCHANDISE',
                    image: '../assets/img/buy-comics-merchandise.png',
                    alt: 'merchandise img'
                },
                {
                    title: 'SUBSCRIPTION',
                    image: '../assets/img/buy-comics-subscriptions.png',
                    alt: 'subscription img'
                },
                {
                    title: 'COMIC SHOP LOCATOR',
                    image: '../assets/img/buy-comics-shop-locator.png',
                    alt: 'shop locator img'
                },
                {
                    title: 'DC POWER VISA',
                    image: '../assets/img/buy-dc-power-visa.svg',
                    alt: 'power visa img'
                },
            ],
        }
    },

    methods: {
        image(img) {
            return new URL(`${img}`, import.meta.url).href
        }
    }
}
</script>

<template>
    <div class="bg-banner">
        <div class="container py-5">
            <div class="d-flex py-2 gap-2">
                <div class="d-flex align-items-center gap-2 " v-for="singleItem in bannerItems">
                    <div class="img-container"> 
                    <img class="img-width" :src="image(singleItem.image)" alt="{{ singleItem.alt }}">
                    </div>

                    <h6 class="img-title">{{ singleItem.title }}</h6>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variable" as *;

.bg-banner {
    background-color: $my-color-primary;
}
.img-container{
    width: 30%;
}
.img-width {
    object-fit: contain;
    width: 100%;
    max-height: 70px;}

.img-title {
    color: $my-color-text;
}
</style>