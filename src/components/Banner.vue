<script>
export default {

}
</script>

<template>
    <div class="bg-banner">
        <div class="container py-5">
            <div class="d-flex py-2">
                <div class="d-flex align-items-center gap-2">
                    <img  class="img-width" src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <h5 class="img-title">DIGITAL COMICS</h5>
                </div>
                <div class="d-flex align-items-center gap-2">
                    <img  class="img-width" src="../assets/img/buy-comics-merchandise.png" alt="">
                    <h5 class="img-title">DC MERCHANDISE</h5>
                </div>
                <div class="d-flex align-items-center gap-2">
                    <img  class="img-width" src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <h5 class="img-title">SUBSCRIPTION</h5>
                </div>
                <div class="d-flex align-items-center gap-2">
                    <img  id="df-width" src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <h5 class="img-title">COMIC SHOP LOCATOR</h5>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variable" as *;

.bg-banner{
    background-color: $my-color-primary;
}

.img-width{
width: 25%;
}

#df-width{
    width: 20%;
}

.img-title{
    color: $my-color-text;
}
</style>