<template>
  <v-app :style="{background: $vuetify.theme.themes.light.background}">
    <v-container>
      <v-row>
        <v-col cols="12" md="4">
          <v-text-field label="Search items" prepend-icon="search" color="red" error></v-text-field>
        </v-col>
        <v-spacer></v-spacer>
        <span class="red--text mt-9">29 items</span>
        <v-btn text class="mt-7" color="red">
          <v-icon color="red" class="mr-n10">menu</v-icon>
        </v-btn>
        <v-btn text class="mt-7" color="red">
          <v-icon color="red" class="mr-n10">dashboard</v-icon>
        </v-btn>
      </v-row>

      <v-row>
        <v-col cols="12" md="3" class="md-4">
          <v-hover v-slot:default="{hover}">
            <v-card max-hieght="250" max-width="250" align="center">
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn icon>
                  <v-icon>edit</v-icon>
                </v-btn>
              </v-card-actions>
              <v-img src="01.png" width="200" height="200"></v-img>
              <v-card-text class="red--text">Air Max Hyper Agressor</v-card-text>
              <v-expand-transition>
                <div
                  v-if="hover"
                  class="d-flex transition-fast-in-fast-out red v-card--reveal display-3 white--text"
                  style="height: 100%"
                >
                  <v-btn outlined color="white">Details</v-btn>
                </div>
              </v-expand-transition>
              <v-btn absolute="" color="red" class="white--text" large fab top left>
              <h1>1</h1>
              </v-btn>
            </v-card>
          </v-hover>
        </v-col>

         <v-col cols="12" md="3" class="md-4">
          <v-hover v-slot:default="{hover}">
            <v-card max-hieght="250" max-width="250" align="center">
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn icon>
                  <v-icon>edit</v-icon>
                </v-btn>
              </v-card-actions>
              <v-img src="01.png" width="200" height="200"></v-img>
              <v-card-text class="red--text">Air Max Hyper Agressor</v-card-text>
              <v-expand-transition>
                <div
                  v-if="hover"
                  class="d-flex transition-fast-in-fast-out red v-card--reveal display-3 white--text"
                  style="height: 100%"
                >
                  <v-btn outlined color="white">Details</v-btn>
                </div>
              </v-expand-transition>
              <v-btn absolute="" color="red" class="white--text" large fab top left>
              <h1>1</h1>
              </v-btn>
            </v-card>
          </v-hover>
        </v-col>

         <v-col cols="12" md="3" class="md-4">
          <v-hover v-slot:default="{hover}">
            <v-card max-hieght="250" max-width="250" align="center">
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn icon>
                  <v-icon>edit</v-icon>
                </v-btn>
              </v-card-actions>
              <v-img src="01.png" width="200" height="200"></v-img>
              <v-card-text class="red--text">Air Max Hyper Agressor</v-card-text>
              <v-expand-transition>
                <div
                  v-if="hover"
                  class="d-flex transition-fast-in-fast-out red v-card--reveal display-3 white--text"
                  style="height: 100%"
                >
                  <v-btn outlined color="white">Details</v-btn>
                </div>
              </v-expand-transition>
              <v-btn absolute="" color="red" class="white--text" large fab top left>
              <h1>1</h1>
              </v-btn>
            </v-card>
          </v-hover>
        </v-col>

         <v-col cols="12" md="3" class="md-4">
          <v-hover v-slot:default="{hover}">
            <v-card max-hieght="250" max-width="250" align="center">
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn icon>
                  <v-icon>edit</v-icon>
                </v-btn>
              </v-card-actions>
              <v-img src="01.png" width="200" height="200"></v-img>
              <v-card-text class="red--text">Air Max Hyper Agressor</v-card-text>
              <v-expand-transition>
                <div
                  v-if="hover"
                  class="d-flex transition-fast-in-fast-out red v-card--reveal display-3 white--text"
                  style="height: 100%"
                >
                  <v-btn outlined color="white">Details</v-btn>
                </div>
              </v-expand-transition>
              <v-btn absolute="" color="red" class="white--text" large fab top left>
              <h1>1</h1>
              </v-btn>
            </v-card>
          </v-hover>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
  computed: {
    theme() {
      return this.$vuetify.theme.dark ? "dark" : "light";
    }
  }
};
</script>

<style>
.v-card--reveal {
  align-items: center;
  bottom: 0;
  justify-content: center;
  opacity: 0.5;
  position: absolute;
  width: 100%;
}
</style>
