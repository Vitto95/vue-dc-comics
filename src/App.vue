<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
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
  list-style: none;
}

a {
  text-decoration: none;
}

.container {
  width: 1000px;
  height: 100%;
  margin: 0 auto;
}
</style>
