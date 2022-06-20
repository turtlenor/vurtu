<template>
  <v-container class="align-center">
    <v-row>
      <v-col>
        <v-img
          src="https://scontent.fosl4-1.fna.fbcdn.net/v/t1.18169-9/24177099_10214220108752916_6131087866811215149_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=8bfeb9&_nc_ohc=9JlWdSZ9kbkAX9BE1oW&_nc_ht=scontent.fosl4-1.fna&oh=00_AT9YPlvGOatmIRbJVC68WMglpclmTPAxFMHhVLgX7Tt-_A&oe=62D789E6"
          transition="scale-transition"
          max-width="300"
          max-height="300"
          class="pa-4 secondary text-no-wrap rounded-pill"
        >
        </v-img>
        <h2>Vil du suge en fjært Frida?</h2>
      </v-col>
    </v-row>
    <v-row>
      <v-btn class="clickFart">Ja</v-btn>
      <v-btn>Nei</v-btn>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "HelloWorld",

  data: () => ({}),
});
</script>
