
<script>
export default {

}
</script>

<template>
  <footer>

    <div class="container py-4">

      <div class="d-flex">

        <div class="pe-5">
          <div class="pb-5">
            <div class="text-white fw-bold pb-2">DC COMICS</div>
            <ul class="nav">
              <li class="nav-item">
                <a class="nav-link" href="#">Charactres</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Comics</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Movies</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">TV</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Games</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Videos</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">News</a>
              </li>
            </ul>
          </div>

          <div>
            <div class="text-white fw-bold pb-2">SHOP</div>
            <ul class="nav">
              <li class="nav-item">
                <a class="nav-link" href="#">Shop DC</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Shop DC Collectibles</a>
              </li>
            </ul>
          </div>
        </div>

        <div class="pe-5">
          <div class="text-white fw-bold pb-2">DC</div>
          <ul class="nav">
            <li class="nav-item">
              <a class="nav-link" href="#">Terms Of Use</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Privacy Policy (New)</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Ad Choices</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Advertising</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Jobs</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Subscription</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Talent Workshops</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">CPSC Certificates</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Ratings</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Shop Help</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Contact Us</a>
            </li>
          </ul>
        </div>

        <div>
          <div class="text-white fw-bold pb-2">SITES</div>
          <ul class="nav">
            <li class="nav-item">
              <a class="nav-link" href="#">DC</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">MAD Magazine</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">DC Kids</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">DC Universe</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">DC Power Visa</a>
            </li>
          </ul>

        </div>
        <div class="img-footer">
          <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
      </div>


    </div>
  </footer>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variable" as *;

.nav {
  --bs-nav-link-padding-x: 1rem;
  --bs-nav-link-padding-y: 0.5rem;
  --bs-nav-link-font-weight: ;
  --bs-nav-link-color: #959595;
  display: block;
}

.nav-link {
  padding: var(--bs-nav-link-padding-y) var(--bs-black);
}

footer {
  background-image: url(../assets/img/footer-bg.jpg);
  background-repeat: no-repeat;
}

.img-footer {
  position: relative;
  width: 50%;
}

.img-footer>img {
  position: absolute;
  top: 50%;
  transform: translate(55px, -50%);
  object-fit: cover;
}
</style>

