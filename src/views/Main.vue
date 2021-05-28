<template>
  <div>
    <Header />
    <Content />
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header";
import Footer from "../components/Footer";
import Content from "../components/FrontPage/FrontPage";

export default {
  components: {
    Header,
    Footer,
    Content,
  },
};
</script>
