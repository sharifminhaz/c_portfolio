<template>
  <v-app>
    <v-main>
      <HeaderApp />
      <BodyComponent/>
      <AboutUs/>
    </v-main>
  </v-app>
</template>

<script>
import HeaderApp from "@/components/HeaderApp";
import BodyComponent from "@/components/BodyComponent";
import AboutUs from "@/components/AboutUs";

export default {
  name: 'App',

  components: {
    AboutUs,
    BodyComponent,
    HeaderApp,
  },

  data: () => ({
    //
  }),
};
</script>
