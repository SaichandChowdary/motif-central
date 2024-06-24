<template>
  <NavComponent />
  <HeaderComponent :title="'GCPR Motif Central Page'" />
  <ProteinComponent />
  <FooterComponent />
</template>

<script>
import HeaderComponent from "./HeaderComponent.vue";
import NavComponent from "./NavComponent.vue";
import ProteinComponent from "./ProteinComponent.vue";
import FooterComponent from "./FooterComponent.vue";
export default {
  components: {
    HeaderComponent,
    NavComponent,
    ProteinComponent,
    FooterComponent,
  },
  name: "LandingComponent",
};
</script>
