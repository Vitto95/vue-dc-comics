<template>
  <footer>
    <div class="container">
      <div class="footer-top">
        <div class="menu-left-footer">
          <div class="col">
            <ul>
              <li>
                <a href="#">DC COMICS</a>
              </li>
              <li>
                <a href="#">Characters</a>
              </li>
              <li>
                <a href="#">Comics</a>
              </li>
              <li>
                <a href="#">Movies</a>
              </li>
              <li>
                <a href="#">TV</a>
              </li>
              <li>
                <a href="#">Games</a>
              </li>
              <li>
                <a href="#">Videos</a>
              </li>
              <li>
                <a href="#">News</a>
              </li>
              <li>
                <a href="#">SHOP</a>
              </li>
              <li>
                <a href="#">Shop DC</a>
              </li>
              <li>
                <a href="#">Shop DC Collectibles</a>
              </li>
            </ul>
          </div>
          <div class="col">
            <li>
              <a href="#">DC</a>
            </li>
            <li>
              <a href="#">Term of Use</a>
            </li>
            <li>
              <a href="#">Privacy Policy (New)</a>
            </li>
            <li>
              <a href="#">Ad Choices</a>
            </li>
            <li>
              <a href="#">Advertising</a>
            </li>
            <li>
              <a href="#">Jobs</a>
            </li>
            <li>
              <a href="#">Subscriptions</a>
            </li>
            <li>
              <a href="#">Talent Workshops</a>
            </li>
            <li>
              <a href="#">CPSC Certificates</a>
            </li>
            <li>
              <a href="#">Ratings</a>
            </li>
            <li>
              <a href="#">Show Help</a>
            </li>
            <li>
              <a href="#">Contact Us</a>
            </li>
          </div>
          <div class="col">
            <li>
              <a href="#">SITES</a>
            </li>
            <li>
              <a href="#">DC</a>
            </li>
            <li>
              <a href="#">MAD Magazine</a>
            </li>
            <li>
              <a href="#">DC Kids</a>
            </li>
            <li>
              <a href="#">DC Universe</a>
            </li>
            <li>
              <a href="#">DC Power Visa</a>
            </li>
          </div>
        </div>
        <div class="logo-right"></div>
      </div>
    </div>

    <div class="banner-bottom">
      <div class="container">
        <div class="banner-left">
          <button>SIGN-UP NOW!</button>
        </div>
        <div class="banner-right">
          VARI SOCIAL
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
.container {
  height: 330px;
}

footer {
  width: 100%;
  height: 460px;
  /*   background-color: lightcoral;
 */
  background-image: url("../assets/img/footer-bg.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  /*   background-image: url("../assets/img/dc-logo-bg.png");*/

  .footer-top {
    display: flex;
    width: 100%;
    height: 330px;
    .menu-left-footer {
      display: flex;
      width: 50%;
      height: 100%;
    }
    .logo-right {
      width: 50%;
      height: 100%;
      background-image: url("../assets/img/dc-logo-bg.png");
      background-size: 100%;
      background-position: center;
    }
  }
}

.col {
  width: 100px;
  color: white;
}

/* menu left footer */

.banner-bottom {
  height: 110px;
  background-color: #303030;
}
</style>
