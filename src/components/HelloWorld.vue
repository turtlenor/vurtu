<template>
  <v-container>
    <v-row>
      <v-col>
        <v-img
          src="https://scontent.fosl4-1.fna.fbcdn.net/v/t31.18172-8/27798207_10155258150000857_9059556998327436468_o.jpg?_nc_cat=105&ccb=1-7&_nc_sid=09cbfe&_nc_aid=0&_nc_ohc=0GdQzIi1gvoAX9Xi4OR&_nc_ht=scontent.fosl4-1.fna&oh=00_AT8KaOlSnKPZ-XomqyMwBMOyrd-SJscWYTvVAFEG7ITInQ&oe=62CA50F8"
          transition="scale-transition"
          max-width="300"
          max-height="300"
          class="pa-4 secondary text-no-wrap rounded-pill"
        >
        </v-img>
        <h2>Vil du suge en fjært ruben?</h2>
      </v-col>
    </v-row>
    <v-row>
      <v-btn>Ja</v-btn>
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
