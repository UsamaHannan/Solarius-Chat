<template>
  <v-container fluid class="grey lighten-5">
    <v-row>
      <v-col>
        <div><h3 class="head1">Monthly Pinned</h3></div>
      </v-col>
      <v-col>
        <div class="check"><span>View All</span></div>
      </v-col>
    </v-row>

    <div>
      <v-card outlined>
        <v-list-item three-line>
          <v-list-item-content>
            <span class="text1">Next-gen immuno</span>
            <h3 class="text2">Multispecific liquids analysis</h3>
            <p class="text3">
              <v-icon> mdi mdi-numeric-1-circle-outline </v-icon>
              New Feedback
            </p>
          </v-list-item-content>
          <div class="one">5d</div>
        </v-list-item>
      </v-card>
    </div>

    <div>
      <v-card class="mx-auto" outlined>
        <v-list-item three-line>
          <v-list-item-content>
            <span class="text1">Harmony</span>
            <h3 class="text2">Protein characterization</h3>
            <p class="text3">
              <v-icon> mdi mdi-alert-circle-outline </v-icon>
              Deadline is today
            </p>
          </v-list-item-content>

          1h
        </v-list-item>
      </v-card>
    </div>
    <div>
      <v-card class="mx-auto" outlined>
        <v-list-item three-line>
          <v-list-item-content>
            <span class="text1">Pharmacuetical</span>
            <h3 class="text2">Quick Element dissolution</h3>
            <p class="text2">
              <v-icon> mdi mdi-check-circle-outline </v-icon>
              Accepted
            </p>
          </v-list-item-content>

          7h
        </v-list-item>
      </v-card>
    </div>

    <div class="mainpoint">
      <v-container fluid class="grey lighten-5">
        <v-row class="m-1" no-gutters>
          <v-col>
            <h3 class="text2">My Learnings</h3>
            <p class="text2">
              <small>Your progress of medical lectures</small>
            </p>
          </v-col>
          <v-col>
            <div class="check">
              <v-icon class="text2"> mdi mdi-dots-horizontal </v-icon>
            </div>
          </v-col>
        </v-row>
      </v-container>
    </div>

    <div>
      <v-row class="m-1">
        <v-col>
          <v-card class="d-flex justify-start mb-6">
            <v-list-item>
              <v-list-item-avatar>
                <v-icon> mdi mdi-shield-bug </v-icon>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title> <h4>Viruses</h4></v-list-item-title>

                <v-list-item-subtitle
                  ><span>96% progress</span></v-list-item-subtitle
                >
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
        <v-col>
          <v-card>
            <v-list-item>
              <v-list-item-avatar>
                <v-icon> mdi mdi-bacteria </v-icon>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title> <h4>Bacterial Cells</h4></v-list-item-title>

                <v-list-item-subtitle
                  ><span>33% progress</span></v-list-item-subtitle
                >
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
      </v-row>
    </div>

    <div>
      <v-row class="m-1">
        <v-col>
          <v-card class="d-flex justify-start mb-6">
            <v-list-item>
              <v-list-item-avatar>
                <v-icon> mdi mdi-medication </v-icon>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title> <h4>Med Science</h4></v-list-item-title>

                <v-list-item-subtitle
                  ><span>7% progress</span></v-list-item-subtitle
                >
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
        <v-col>
          <v-card>
            <v-list-item>
              <v-list-item-avatar>
                <v-icon> mdi mdi-gentoo </v-icon>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title> <h4>Human Gens</h4></v-list-item-title>

                <v-list-item-subtitle
                  ><span>58% progress</span></v-list-item-subtitle
                >
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
      </v-row>
    </div>
  </v-container>
</template>

<script>
export default {
  name: "MainTabs",

  data: () => ({}),
};
</script>

<style>
.check {
  display: flex;
  justify-content: end;
}
.head1 {
  margin-bottom: 15px;
}
.text1 {
  margin: 5px 0px 5px 0px !important;
}
.text2 {
  margin: 5px 0px 5px 0px !important;
}
.text3 {
  margin: 5px 0px 5px 0px !important;
}
.mainpoint {
  margin-top: 10px;
}
</style>
