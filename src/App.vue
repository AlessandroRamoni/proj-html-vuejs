<template>
  <div id="app">
    <NavComponent />
    <HeaderComponent />
    <MainComponent />
    <StatisticsComponent />
    <OurClassesComponent />
    <BambiniComponent />
    <BoardComponent />
    <OurStaffComponent />
    <FeedbackComponent />
    <NewsComponent />
  </div>
</template>

<script>
import NavComponent from "@/components/NavComponent.vue";
import HeaderComponent from "@/components/HeaderComponent.vue";
import MainComponent from "@/components/MainComponent.vue";
import StatisticsComponent from "@/components/StatisticsComponent.vue";
import OurClassesComponent from "@/components/OurClassesComponent.vue";
import BambiniComponent from "@/components/BambiniComponent.vue";
import BoardComponent from "@/components/BoardComponent.vue";
import OurStaffComponent from "@/components/OurStaffComponent.vue";
import FeedbackComponent from "@/components/FeedbackComponent.vue";
import NewsComponent from "@/components/NewsComponent.vue";

export default {
  name: "App",
  components: {
    NavComponent,
    HeaderComponent,
    MainComponent,
    StatisticsComponent,
    OurClassesComponent,
    BambiniComponent,
    BoardComponent,
    OurStaffComponent,
    FeedbackComponent,
    NewsComponent,
  },
};
</script>

<style lang="scss">
@import "@/assets/style/standard.scss";
@import url("https://fonts.googleapis.com/css2?family=Gemunu+Libre&family=Open+Sans&display=swap");
#app {
  font-family: "Open Sans", sans-serif;
}
</style>
