<template>
  <div id="app">
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Main from "@/components/Main.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100vw;
}

ul {
  list-style-type: none;
}

li {
  list-style: none;
}

a {
  text-decoration: none;
}

a:visited {
  color: white;
}

.container {
  width: 1000px;
  height: 100%;
  margin: 0 auto;
}
</style>
