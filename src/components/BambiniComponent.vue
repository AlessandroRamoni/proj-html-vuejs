<template>
  <div id="contenitore">
    <img src="../assets/img/gallery_01.jpg" alt="" />
    <img src="../assets/img/gallery_02.jpg" alt="" />
    <img src="../assets/img/gallery_03.jpg" alt="" />
    <img src="../assets/img/gallery_04.jpg" alt="" />
  </div>
</template>

<script>
export default {
  name: "BambiniComponent",
};
</script>

<style scoped lang="scss">
#contenitore {
  display: flex;
  img {
    max-width: 25%;
  }
}
</style>