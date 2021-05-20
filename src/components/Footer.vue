<template>
  <footer>
    <div class="container">
      <div class="footer-top">
        <div class="menu-left-footer"></div>
        <div class="logo-right">
          <!-- <img src="../assets/img/dc-logo-bg.png" alt="" /> -->
        </div>
      </div>
    </div>

    <div class="banner-bottom">
      <div class="container">
        bottom
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

.banner-bottom {
  height: 110px;
  background-color: #303030;
}
</style>
