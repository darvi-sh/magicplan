<template>
  <v-app>
    <!-- <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Vuetify</span>
        <span class="font-weight-light">MATERIAL DESIGN</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        text
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >
        <span class="mr-2">Latest Release</span>
      </v-btn>
    </v-app-bar> -->

    <v-content>
      <!-- <HelloWorld/> -->
    	<div class="my-5 py-5 headline blue--text text--darken-2 text-center">Find the Pricing Model that Fits Your Needs the Best.</div>
      <PricePlans />
    </v-content>
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld';
import PricePlans from './components/PricePlans';

export default {
  name: 'App',
  components: {
    // HelloWorld,
    PricePlans,
  },
  data: () => ({
    //
  }),
};
</script>
