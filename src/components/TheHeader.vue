
<script>
export default {

}
</script>

<template>
  <header class="my-4">
    <div class="container">
      <div class="d-flex align-items-center justify-content-between">
        <div class="nav-image">
          <img src="../assets/img/dc-logo.png" alt="">
        </div>

        <div>
          <ul class="nav">
            <li class="nav-item">
              <a class="nav-link" href="#">CHARACTERS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">COMICS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">MOVIES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">TV</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">GAMES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">COLLECTIBLES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">VIDEOS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">FANS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">NEWS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">SHOP</a>
            </li>
          </ul>

        </div>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variable" as *;

.nav {
    --bs-nav-link-font-weight: 450 ;
    --bs-nav-link-color: black;
}

.nav-link {
    padding: 8px;
    font-size: 16px;
}

.nav-image img{
  width: 70px;
}

.nav-link .active{
  color: $my-color-primary ;
}

</style>

