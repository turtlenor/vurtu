<template>
  <v-container class="align-center">
    <v-row>
      <v-col>
        <v-img
          src="https://scontent.fosl4-2.fna.fbcdn.net/v/t1.6435-9/39056495_10214340028907082_2163652468997619712_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=t6j-mbBjNcUAX99ok2g&tn=97WA1bD08EkRTirD&_nc_ht=scontent.fosl4-2.fna&oh=00_AT9M7WSIGTfNZ34CpgKfTYjHVaeej06jh1a-zrxGcTw88Q&oe=62C9ABA9"
          transition="scale-transition"
          max-width="300"
          max-height="300"
          class="pa-4 secondary text-no-wrap rounded-pill"
        >
        </v-img>
        <h2>Vil du suge en fjært Edvard?</h2>
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
