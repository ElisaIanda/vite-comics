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

                <h4>FOLLOW US</h4>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variable" as *;

.bg-piepagina{
    background-color: $my-color-secondary;
}
h4{
    color: $my-color-primary;
}

button{
    border-color: $my-color-primary;
    background-color: transparent;
    color: $my-color-text;
    font-size: 1.5rem;
}
</style>