<template>
  <header-component></header-component>
  <panel-component></panel-component>
  <description-component></description-component>
  <works-description></works-description>
  <choose-component></choose-component>
  <services-component></services-component>
  <notice-component></notice-component>
  <review-component></review-component>
  <orderComponent></orderComponent>
  <footer-component></footer-component>
</template>

<script>
import headerComponent from "@/components/headerComponent.vue";
import panelComponent from "@/components/panelComponent.vue";
import descriptionComponent from "@/components/descriptionComponent.vue";
import worksDescription from "@/components/worksComponent.vue";
import chooseComponent from "@/components/chooseComponent.vue";
import servicesComponent from "@/components/servicesComponents.vue";
import noticeComponent from "@/components/noticeComponent.vue";
import reviewComponent from "@/components/reviewComponent.vue";
import orderComponent from "@/components/orderComponent.vue";
import footerComponent from '@/components/footerComponent.vue'

export default {
  components: {
    headerComponent,
    panelComponent,
    descriptionComponent,
    worksDescription,
    chooseComponent,
    servicesComponent,
    noticeComponent,
    reviewComponent,
    orderComponent,
    footerComponent
  },
};
</script>

<style scoped></style>
