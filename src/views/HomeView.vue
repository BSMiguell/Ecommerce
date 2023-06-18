<template>
  <v-app>
    <NavBar class="index" />
    <DashBoard class="index" />
    <FooterView class="index" />
  </v-app>
</template>

<script>
import NavBar from "../components/NavBar";
import DashBoard from "../components/DashBoard";
import FooterView from "../components/FooterView";

export default {
  name: "HomeView",

  components: {
    NavBar,
    DashBoard,
    FooterView,
  },
};
</script>

<style scoped></style>
