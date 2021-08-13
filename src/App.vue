<template>
  <div id="app">
    <h1>My todos</h1>
    <div class="todoList">
      <main-header></main-header>
      <list></list>
      <main-footer></main-footer>
    </div>
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

<style lang="scss">
h1 {
  text-align: center;
  padding: 30px;
  font-weight: 200;
}
.todoList {
  width: 450px;
  border: 1px solid rgb(176, 176, 176);
  padding: 10px;
  margin: auto;
  border-radius: 10px;
}
</style>
