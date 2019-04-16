<template>
  <div class="alert">
    <div class="cover"></div>
    <div class="content">
      <slot></slot>
    </div>
  </div>
</template>
<script>
export default {
  name: "Alert"
};
</script>
<style lang="scss" scoped>
.cover {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba($color: #000000, $alpha: 0.3);
}
.content {
  position: fixed;
  top: 50%;
  left: 50%;
  background-color: #fff;
  border-radius: 5px;
  transform: translate(-50%, -50%);
}
</style>


