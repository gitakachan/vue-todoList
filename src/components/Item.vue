<template>
  <div class="item" @mouseenter="isHover = true" @mouseleave="isHover = false">
    <input class="checkbox" type="checkbox" name="" id="" />
    <label class="content" for="">study English</label>
    <button v-show="isHover">x</button>
  </div>
</template>
<script>
export default {
  name: "Item",
  data() {
    return {
      isHover: false,
    };
  },
};
</script>
<style lang="scss">
.item {
  display: flex;
  padding: 5px 10px;
  .checkbox {
    margin: 5px 10px 5px 0;
  }

  button {
    width: 20px;
    height: 20px;
    background-color: transparent;
    border: none;
    margin-left: auto;
    cursor: pointer;
    &:hover {
      color: rgb(135, 13, 13);
    }
  }

  &:hover {
    background-color: rgb(233, 210, 176);
  }
}
</style>
