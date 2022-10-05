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
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
