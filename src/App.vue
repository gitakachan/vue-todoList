<template>
  <div id="app">
    <main-header></main-header>
    <list></list>
    <main-footer></main-footer>
  </div>
</template>

<script>
import List from "./components/List.vue";
import MainHeader from "./components/MainHeader.vue";
import MainFooter from "./components/MainFooter.vue";
export default {
  name: "App",
  components: {
    List,
    MainHeader,
    MainFooter,
  },
};
</script>

<style lang="scss"></style>
