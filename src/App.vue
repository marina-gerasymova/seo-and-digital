<template>
  <div id="app">
    <Header />
    <Content />
    <Footer />
  </div>
</template>

<script>
import "./style/main.scss";
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import Content from "./components/FrontPage.vue";

export default {
  components: {
    Header,
    Footer,
    Content,
  },
};
</script>
