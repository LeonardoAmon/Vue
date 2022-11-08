<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
    <v-toolbar-title>Most Used Words</v-toolbar-title>
    </v-app-bar>

    <v-main>
      <HomeDisplayVue />
    </v-main>
  </v-app>
</template>

<script>
import HomeDisplayVue from './components/HomeDisplay.vue';


export default {
  name: 'App',

  components: {
    HomeDisplayVue
  },

  data: () => ({
    //
  }),
};
</script>
