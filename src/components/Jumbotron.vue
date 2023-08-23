<script>
export default {

}
</script>

<template>
    <div class="jumbo">
        <div class="container">
            <div class="btn-series">
                <h5>CURRENT SERIES</h5>
            </div>
        </div>
    </div>
</template>


<style lang="scss" scoped>
@use "../styles/partials/variable" as *;

.jumbo {
    background-image: url(../assets/img/jumbotron.jpg);
    height: 400px;
    position: relative;
}

.btn-series {
    width: 14%;
    background-color: $my-color-primary;
    position: absolute;
    height: 50px;
    top: 380px;
    display: flex;
    justify-content: center;
    align-items: center;
    left: 45px;
    color: $my-color-text;
}

h5{
    margin: 0;
}
</style>