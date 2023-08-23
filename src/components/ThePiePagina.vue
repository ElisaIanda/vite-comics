<script>
export default {

}
</script>

<template>
    <div class="bg-piepagina py-4">
        <div class="container">
            <div class="d-flex align-items-center justify-content-between">
                <button>
                    SIGN-UP NOW!
                </button>

                <div class="d-flex align-items-center gap-3">
                    <h4>FOLLOW US</h4>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">

                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variable" as *;

.bg-piepagina {
    background-color: $my-color-secondary;
}

h4 {
    color: $my-color-primary;
}

button {
    border-color: $my-color-primary;
    background-color: transparent;
    color: $my-color-text;
    font-size: 1.5rem;
}
</style>