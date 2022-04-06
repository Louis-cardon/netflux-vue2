<template>
  <v-app>
    <v-main>
      <nav-bar/>
      <caroussel/>
    </v-main>
  </v-app>
</template>

<script>
import navBar from "@/components/NavBar";
import caroussel from "@/components/caroussel";

export default {
  name: 'App',

  components: {
    navBar,
    caroussel,
  },

  data: () => ({
    //
  }),
};
</script>
