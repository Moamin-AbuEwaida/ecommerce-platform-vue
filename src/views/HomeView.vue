<template>
  <v-app>
    <Navbar class="index" />
    <Dashbaord />
    <Footer />
  </v-app>
</template>

<script>
import Dashbaord from "@/components/Dashbaord.vue";
import Navbar from "../components/Navbar";
import Footer from "@/components/Footer.vue";

export default {
  name: "HomeView",

  components: {
    Navbar,
    Dashbaord,
    Footer,
  },
};
</script>

<style scoped>
.index {
  z-index: 999;
}
</style>
