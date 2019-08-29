<template lang="html">
  <v-container fluid>
    <v-container>
      <v-row justify="space-between">

        <v-col cols="4">
          <h3 class="title font-weight-black">LATER</h3>
          <p class="font-weight-light mb-0">Copyright © 2018 LATERAL.</p>
          <p class="font-weight-light mb-12">All Rights Reserved. Proudly made in EU.</p>

          <v-row justify="start" >
              <a href="#">
                <v-img
                height="30"
                contain
                :src="require('../assets/social/twitter.png')" />
              </a>
              <a href="#">
                <v-img
                height="30"
                contain
                :src="require('../assets/social/facebook.png')" />
              </a>
              <a href="#">
                <v-img
                height="30"
                contain
                :src="require('../assets/social/linkedin.png')" />
              </a>
          </v-row>
        </v-col >

        <v-col cols="2">
          <h3 class="title font-weight-black">Company</h3>
          <v-row><v-btn
          class=" "
          text
          target="_blank"
          >
            About
          </v-btn></v-row>
          <v-row><v-btn
          class=" "
          text
          target="_blank"
          >
            Carrers
          </v-btn></v-row>
          <v-row><v-btn
          class=" "
          text
          target="_blank"
          >
            Awards
          </v-btn></v-row>
          <v-row><v-btn
          class=" "
          text
          target="_blank"
          >
            Users Program
          </v-btn></v-row>
          <v-row><v-btn
          class=" "
          text
          target="_blank"
          >
            Locations
          </v-btn></v-row>
        </v-col>
        <v-col cols="2">
          <h3 class="title font-weight-black">Products</h3>
          <v-row><v-btn
          class=" "
          text
          target="_blank"
          >
            Integrations
          </v-btn></v-row>
          <v-row><v-btn
          class=" "
          text
          target="_blank"
          >
            API
          </v-btn></v-row>
          <v-row><v-btn
          class=" "
          text
          target="_blank"
          >
            Pricing
          </v-btn></v-row>
          <v-row><v-btn
          class=" "
          text
          target="_blank"
          >
            Documentation
          </v-btn></v-row>
          <v-row><v-btn
          class=" "
          text
          target="_blank"
          >
            Release Notes
          </v-btn></v-row>
        </v-col>
        <v-col cols="2">
          <h3 class="title font-weight-black">Support</h3>
          <v-row><v-btn
          class=" "
          text
          target="_blank"
          >
            Contact
          </v-btn></v-row>
          <v-row><v-btn
          class=" "
          text
          target="_blank"
          >
            FAQ
          </v-btn></v-row>
          <v-row><v-btn
          class=" "
          text
          target="_blank"
          >
            Press
          </v-btn></v-row>
        </v-col>

      </v-row>
    </v-container>
  </v-container>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
.container--fluid{
  background-color: #f0e8f7;
  background-image: url('~@/assets/footer-bg.jpg');
  background-repeat: no-repeat;
  background-attachment: scroll;
  background-position: top;
  background-size: cover;
  padding-bottom: 5em;
}
.title{
  margin-bottom: 1em;
}
.v-btn{
  text-transform: none !important;
}
</style>
