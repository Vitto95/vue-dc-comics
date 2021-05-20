<template>
  <header>
    <div class="container">
      <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="logo-dc" />
      </div>
      <nav class="menu-right-header">
        <ul>
          <li v-for="(link, index) in links" :key="index">
            <a href="#">{{ link.text }}</a>
          </li>
          <!--  <li>
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
            <a href="#">Collectibles</a>
          </li>
          <li>
            <a href="#">Videos</a>
          </li>
          <li>
            <a href="#">Fans</a>
          </li>
          <li>
            <a href="#">News</a>
          </li>
          <li>
            <a href="#">Shop</a>
          </li> -->
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      links: [
        { text: "Characters", url: "#", current: false },
        { text: "Comics", url: "#", current: false },
        { text: "Movies", url: "#", current: false },
        { text: "TV", url: "#", current: false },
        { text: "Games", url: "#", current: false },
        { text: "Collectibles", url: "#", current: false },
        { text: "Videos", url: "#", current: false },
        { text: "Fans", url: "#", current: false },
        { text: "News", url: "#", current: false },
        { text: "Shop", url: "#", current: false },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
/* Impostazione macroaree */
header {
  width: 100%;
  height: 80px;
  background-color: white;
  .container {
    display: flex;
    background-color: lightcoral;
    .logo {
      display: flex;
      align-items: center;
      width: 30%;
      height: 100%;
      /*       background-color: red;*/
    }
    .menu-right-header {
      display: flex;
      justify-content: flex-end;
      align-items: center;
      width: 70%;
      height: 100%;
      /*  background-color: blue; */
    }
  }
}

/* logo */

.logo img {
  height: 70%;
}

/* menu right */

.menu-right-header ul {
  display: flex;
  li {
    margin-right: 20px;
    li a {
      color: black;
    }
  }
  li:last-child {
    margin-right: 0;
  }
}
</style>
