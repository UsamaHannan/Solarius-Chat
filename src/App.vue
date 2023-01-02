<template>
  <v-container fluid class="grey lighten-5">
    <v-row class="m-1" no-gutters>
      <v-col md="2">
        <MainNav />
      </v-col>
      <v-col md="5">
        <MainPosts />
      </v-col>
      <v-col md="4">
        <MainTabs />
      </v-col>
      <v-col md="1">
        <MainProfile />
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import MainNav from "./components/MainNav";
import MainPosts from "./components/MainPosts";
import MainTabs from "./components/MainTabs";
import MainProfile from "./components/MainProfile";
export default {
  name: "App",

  components: {
    MainNav,
    MainPosts,
    MainTabs,
    MainProfile,
  },

  data: () => ({}),
};
</script>
<style>
html, body{
  overflow-y: hidden;
}
</style>
