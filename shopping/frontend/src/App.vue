<template>
  <v-app>
    <Nav/>
    <router-view/>
  </v-app>
</template>

<script>
import Nav from "./components/Nav"

export default {
  name: "App",

  components: {
    Nav
  },

  data: () => ({
    //
  })
};
</script>
