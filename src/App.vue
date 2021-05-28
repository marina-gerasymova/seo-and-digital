<template>
  <div id="app">
    <component :is="layout">
      <router-view />
    </component>
  </div>
</template>

<script>
import "./style/main.scss";
import Main from "./views/Main";
import Error from './views/404'

export default {
  components: {
    Main,
    Error,
  },
  computed: {
    layout() {
      return this.$route.meta.layout || 'error'
    }
  },
};
</script>
