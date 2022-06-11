<template>
  <v-app>
    <v-app-bar app color="teal darken-4" dark>
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2 pl-20"
          contain
          src="https://upload.wikimedia.org/wikipedia/commons/2/2f/Logo_TV_2015.svghttps://upload.wikimedia.org/wikipedia/commons/2/2f/Logo_TV_2015.svg"
          transition="scale-transition"
          width="40"
        />
        <span>
          <v-card-text>Adrian Karlsen</v-card-text>
        </span>
      </div>
      <div class="d-flex align-right">
        <v-btn class="teal darken-1 white--text"> Hjem</v-btn>
        <v-btn class="teal darken-1 white--text">Om meg</v-btn>
      </div>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "App",

  data: () => ({
    //
  }),
});
</script>
