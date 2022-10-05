<template>
  <div id="app">
    <NavComponent />
    <HeaderComponent />
  </div>
</template>

<script>
import NavComponent from "@/components/NavComponent.vue";
import HeaderComponent from "@/components/HeaderComponent.vue";

export default {
  name: "App",
  components: {
    NavComponent,
    HeaderComponent,
  },
};
</script>

<style lang="scss">
@import "@/assets/style/standard.scss";
#app {
}
</style>
