<template lang="html">
  <v-container>
    <Header/>
    <v-container fill-height>
      <v-row >
        <v-col cols="6">
          <h1>Build applications <span class="color-purple">faster</span></h1>

        </v-col>
        <v-col cols="7">
          <p class="texto-grande">Hire experts & get your job done. The right IT security solutions. Protect your clients and computer systems from hackers and fight against malware.</p>

        </v-col>
        <v-col cols="12">
          <p class="color-blue">For as low as <span class="color-purple">$0.95</span> per user account</p>

        </v-col>
        <v-col cols="12">
          <v-btn
            id="login"
            color="#66cccc"
            dark
            depressed
            class="ma-2"
            rounded
            target="_blank"
          >
            <span>WATCH DEMO</span>
          </v-btn>
          <v-btn
          id="login"
          color="#9966cc"
          class="ma-2 "
          rounded
          depressed
          dark
          target="_blank"
          >
            <span>START NOW</span>
          </v-btn>
        </v-col>
      </v-row>
    </v-container>
  </v-container>
</template>

<script>
import Header from './Header'

export default {
  name: 'App',
  components: {
    Header
  },
  data: () => ({
    //
  }),
};
</script>

<style lang="css" scoped>
</style>
