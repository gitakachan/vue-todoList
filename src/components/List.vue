<template>
  <div class="list border-gray">
    <item></item>
    <item></item>
    <item></item>
  </div>
</template>
<script>
import Item from "./Item.vue";
export default {
  components: { Item },
  name: "List",
  data() {
    return {};
  },
};
</script>
<style lang="scss">
.list {

  margin: 10px 0;
  border-radius: 5px;
}
</style>
