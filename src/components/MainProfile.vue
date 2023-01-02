<template>
  <div>
    <div class="profile">
      <v-badge
        bordered
        bottom
        color="deep-purple accent-4"
        dot
        offset-x="12"
        offset-y="15"
        class="circle"
      >
        <v-avatar size="60">
          <v-img src="https://cdn.vuetifyjs.com/images/lists/2.jpg"></v-img>
        </v-avatar>
      </v-badge>
    </div>
    <div>
      <h4 class="profile">Dr. Saim</h4>
      <span class="profile1">Scientist</span>
    </div>

    <div class="bordr1"></div>

    <div class="profile">
      <v-btn class="mx-2" fab small outlined color="black">
        <v-icon dark> mdi-pencil </v-icon>
      </v-btn>
    </div>

    <div class="profile">
      <v-btn class="mx-2" fab small outlined color="black">
        <v-icon dark> mdi-message-text </v-icon>
      </v-btn>
    </div>

    <div class="profile">
      <v-btn class="mx-2" fab dark color="indigo">
        <v-icon dark> mdi-plus </v-icon>
      </v-btn>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainProfile",

  data: () => ({}),
};
</script>

<style>
.theme--light.v-badge .v-badge__badge::after {
  /* border-color: #7e3f3f; */
  background-color: #02a302;
}

.profile {
  display: flex;
  justify-content: center;
  margin-top: 15px;
}
.profile1 {
  display: flex;
  justify-content: center;
  margin-top: 3px;
}
.bordr1 {
  border: 1px solid white;
  width: 300px;
  height: 320px;
}
</style>
