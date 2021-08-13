<template>
  <div class="header">
    <input class="border-gray" type="text" placeholder="enter a todo" />
  </div>
</template>
<script>
export default {
  name: "Header",
  data() {
    return {};
  },
};
</script>
<style lang="scss">
.header {
  input {
    display: block;
    margin: auto;
    width: 100%;
    padding: 5px 10px;
    border-radius: 5px;

    &:focus {
      outline: none;
    }
  }
}
</style>
