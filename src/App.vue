<template>
  <div id="app">
    <NavDinamica :cards="immagini" />
    <HeaderComponent />
    <MainComponent />
    <!-- <CaroselloComponent :cards="fotografie" /> -->
    <StatisticsComponent />
    <OurClassesComponent />
    <BambiniComponent />
    <BoardComponent />
    <OurStaffComponent />
    <FeedbackComponent />
    <NewsComponent />
    <AddGoogleMap />
    <ContactComponent />
    <FooterComponent />
    <FooterNavComponent :cards="icone" />
  </div>
</template>

<script>
import NavDinamica from "@/components/NavDinamica.vue";
import HeaderComponent from "@/components/HeaderComponent.vue";
import MainComponent from "@/components/MainComponent.vue";
import StatisticsComponent from "@/components/StatisticsComponent.vue";
import OurClassesComponent from "@/components/OurClassesComponent.vue";
import BambiniComponent from "@/components/BambiniComponent.vue";
import BoardComponent from "@/components/BoardComponent.vue";
import OurStaffComponent from "@/components/OurStaffComponent.vue";
import FeedbackComponent from "@/components/FeedbackComponent.vue";
import NewsComponent from "@/components/NewsComponent.vue";
import AddGoogleMap from "@/components/AddGoogleMap.vue";
import ContactComponent from "@/components/ContactComponent.vue";
import FooterComponent from "@/components/FooterComponent.vue";
import FooterNavComponent from "@/components/FooterNavComponent.vue";
// import CaroselloComponent from "@/components/CaroselloComponent.vue";

import { immagini } from "../src/data";
import { icone } from "../src/data";
// import { fotografie } from "../src/data";

export default {
  name: "App",
  data() {
    return {
      immagini,
      icone,
      // fotografie,
    };
  },
  components: {
    NavDinamica,
    HeaderComponent,
    MainComponent,
    StatisticsComponent,
    OurClassesComponent,
    BambiniComponent,
    BoardComponent,
    OurStaffComponent,
    FeedbackComponent,
    NewsComponent,
    AddGoogleMap,
    ContactComponent,
    FooterComponent,
    FooterNavComponent,
    // CaroselloComponent,
  },
};
</script>

<style lang="scss">
@import "@/assets/style/standard.scss";
@import url("https://fonts.googleapis.com/css2?family=Gemunu+Libre&family=Open+Sans&display=swap");
@mixin padding-top {
  padding-top: 50px;
}
#app {
  font-family: "Open Sans", sans-serif;
}
</style>
