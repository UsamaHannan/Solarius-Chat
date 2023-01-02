<template>
  <div>
    <div class="logoo">
      <v-img
        :src="require('../assets/ChatLogo.png')"
        max-height="100"
        max-width="150"
      ></v-img>
    </div>

    <div>
      <template>
        <v-card class="mx-auto" width="300">
          <v-list>
            <v-list-item>
              <v-list-item-icon>
                <v-icon class="icons">mdi-poll</v-icon>
              </v-list-item-icon>

              <v-list-item-title>Dashboard</v-list-item-title>
            </v-list-item>
            <v-list-item>
              <v-list-item-icon>
                <v-icon class="icons">mdi-school</v-icon>
              </v-list-item-icon>

              <v-list-item-title>Education</v-list-item-title>
            </v-list-item>
            <v-list-group :value="true" prepend-icon="mdi-book-multiple">
              <template v-slot:activator>
                <v-list-item-title class="icons1">Resources</v-list-item-title>
              </template>

              <v-list-item v-for="([title, icon], i) in admins" :key="i" link>
                <v-list-item-title v-text="title"></v-list-item-title>

                <v-list-item-icon>
                  <v-icon v-text="icon"></v-icon>
                </v-list-item-icon>
              </v-list-item>
            </v-list-group>

            <v-list-item>
              <v-list-item-icon>
                <v-icon class="icons">mdi-cog</v-icon>
              </v-list-item-icon>

              <v-list-item-title>Settings</v-list-item-title>
            </v-list-item>
          </v-list>
        </v-card>
      </template>
    </div>

    <div class="bordr"></div>

    <div class="buttn">
      <v-btn class="mx-2" fab dark color="indigo">
        <v-icon dark> mdi mdi-exit-to-app </v-icon>
      </v-btn>
      <span class="logout">
        <strong> LogOut</strong>
      </span>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomePage",

  data: () => ({
    admins: [
      ["Management", "mdi-account-multiple-outline"],
      ["Settings", "mdi-cog-outline"],
    ],
    cruds: [
      ["Create", "mdi-plus-outline"],
      ["Read", "mdi-file-outline"],
      ["Update", "mdi-update"],
      ["Delete", "mdi-delete"],
    ],
  }),
};
</script>
<style>
.logoo {
  display: flex;
  justify-content: center;
}

.bordr {
  border: 1px solid white;
  width: 300px;
  height: 120px;
}
.icons {
  margin-right: 10px;
}
.icons1 {
  margin-left: 5px;
}
.buttn {
  margin-bottom: 15px;
  margin-left: 5px;
}
.logout {
  margin-left: 2px;
}
</style>
