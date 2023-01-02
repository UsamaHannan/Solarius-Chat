<template>
  <v-container class="grey lighten-5">
    <v-row no-gutters>
      <v-col>
        <h3 class="span1">Today's Plan</h3>
        <span><small>June 14th, 2022</small></span>
      </v-col>
      <v-col>
        <div class="check">
          <v-btn class="mx-2" fab dark color="indigo">
            <v-icon dark> mdi-plus </v-icon>
          </v-btn>
        </div>
      </v-col>

      <h2 class="headr">Sustainable development goals and health innovation</h2>

      <v-container class="grey lighten-5">
        <v-row class="m-1" no-gutters>
          <v-col>
            <div class="avatar-container">
              <div class="avatar-container-item">
                <img
                  src="https://placekitten.com/300/300"
                  alt=""
                  class="imag"
                />
              </div>
              <div class="avatar-container-item">
                <img
                  src="https://cdn.vuetifyjs.com/images/john.jpg"
                  alt=""
                  class="imag"
                />
              </div>
              <div class="avatar-container-item">
                <img
                  src="https://avatars0.githubusercontent.com/u/9064066?v=4"
                  alt=""
                  class="imag"
                />
              </div>

              <div class="avatar-container-item">
                <v-avatar class="new">
                  <span class="white--text text-h5">+5</span>
                </v-avatar>
              </div>
            </div>
          </v-col>
          <v-col>
            <v-row class="check1">
              <div><h4 class="head">Medi Team Meeting</h4></div>
            </v-row>

            <v-row class="check1">
              <div>
                <span><small>13:30-14:50</small></span>
              </div>
            </v-row>
          </v-col>
        </v-row>
      </v-container>
    </v-row>

    <div class="card1">
      <v-card class="card01" color="#385F73" dark>
        <v-card-title class="text-h5"> Weekly report </v-card-title>

        <v-card-subtitle>Track your perfomance</v-card-subtitle>

        <v-card-actions class="bton">
          <v-btn text class="btnn"> View Report </v-btn>
        </v-card-actions>
      </v-card>
    </div>

    <v-row class="m-1" no-gutters>
      <v-col>
        <div>
          <v-card color="#385F73" dark class="card2">
            <v-card-title class="text-h5 centr1"> Study 78X </v-card-title>

            <v-card-subtitle class="centr">
              <v-icon class="icon1"> mdi mdi-clock-time-four </v-icon>In
              progress</v-card-subtitle
            >
          </v-card>
        </div>
      </v-col>
      <v-col>
        <div>
          <v-card color="#385F73" dark class="card3">
            <v-card-title class="text-h5 centr1"> Analyses </v-card-title>

            <v-card-subtitle class="centr">
              <v-icon class="icon1"> mdi mdi-check-circle </v-icon
              >Completed</v-card-subtitle
            >
          </v-card>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "MainPosts",

  data: () => ({}),
};
</script>

<style>
.check {
  display: flex;
  justify-content: end;
}

.headr {
  margin-top: 20px;
  margin-bottom: 10px;
}

.imag {
  width: 50px;
  height: 50px;
  border-radius: 50%;
}

.new {
  background-color: rgb(75, 75, 75) !important;
  color: white;
}

.avatar-container {
  margin: 10px 10px 15px 10px;

  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
}

.avatar-container-item {
  background-color: grey;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  border: 3px solid white;
  margin-left: -20px;
}

.check1 {
  display: flex;
  justify-content: flex-end;
}

.span1 {
  margin-top: 5px;
  margin-bottom: 5px;
}
.card1 {
  margin: 5px 0px 18px 0px;
}
.card2 {
  margin-right: 10px;
  height: 200px;
  background: url(../assets/3.PNG);
}
.card3 {
  margin-left: 10px;
  height: 200px;
  background: url(../assets/4.PNG);
}
.head {
  margin-top: 24px;
  margin-bottom: 3px;
}
.card01 {
  height: 160px;
  background: url(../assets/2.PNG);
}

.centr {
  display: flex;
  justify-content: center;
}
.centr1 {
  display: flex;
  justify-content: center;
  margin-bottom: 10px;
}
.icon1 {
  margin-right: 5px;
}
.bton {
  margin-top: 15px;
}
.btnn {
  border: 1px solid whitesmoke;
}
.circle1 {
  background-color: black;
}
</style>
