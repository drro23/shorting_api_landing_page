<template>
  <div>
    <div class="container">
      <NavBar />
      <HeaderView />
    </div>
    <div class="content">
      <ShortenLink />
    </div>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import NavBar from "~/components/NavBar.vue";
import HeaderView from "~/components/HeaderView.vue";
import ShortenLink from "~/components/ShortenLink.vue";

export default {
  components: {
    Logo,
    NavBar,
    HeaderView,
    ShortenLink
  },
  head: {
    title: "Home",
    meta: [{ charset: "utf-8" }]
  }
};
</script>

<style>
.content {
  width: 100%;
  background-color: hsl(257, 7%, 63%);
}
.container {
  width: 80%;
  margin: 0 auto;
}
</style>
