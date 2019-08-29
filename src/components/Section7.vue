<template lang="html">
  <v-container fluid>
    <v-container>
      <v-row >
        <v-col cols="4">
          <v-col>
            <v-img
            class="align-start"
            height="60"
            max-width="60"
            contain
            :src="require('../assets/icons/support-64.png')" />
          </v-col>
          <v-col>
            <h3 class="font-weight-black">Help & Support</h3>
          </v-col>
          <v-col cols="2">
            <hr class="rayita">
          </v-col>
          <v-col>
            <p>Our 24/7 support team is here to help you and make sure our product is up to date.</p>
          </v-col>
          <v-btn
          id="login"
          color="#9966cc"
          class="ma-2 "
          rounded
          depressed
          dark
          target="_blank"
          >
            <span class="text-lowercase">support@supportemail.com</span>
          </v-btn>
        </v-col>
        <v-col cols="4">
          <v-col>
            <v-img
            class="align-start"
            height="60"
            max-width="60"
            contain
            :src="require('../assets/icons/globe-64.png')" />
          </v-col>
          <v-col>
            <h3 class="font-weight-black">Media & Press</h3>
          </v-col>
          <v-col cols="2">
            <hr class="rayita">
          </v-col>
          <v-col>
            <p>Online awards and publications. Get our media resource and learn about our company.</p>
          </v-col>
          <v-btn
          id="login"
          color="#9966cc"
          class="ma-2 "
          rounded
          depressed
          dark
          target="_blank"
          >
            <span class="text-lowercase">media@youremail.com</span>
          </v-btn>
        </v-col>
        <v-col cols="4">
          <v-col>
            <v-img
            class="align-start"
            height="60"
            max-width="60"
            contain
            :src="require('../assets/icons/wallet-64.png')" />
          </v-col>
          <v-col class="mail-resaltado">
            <v-col>
              <h3 class="font-weight-black">Sales</h3>
            </v-col>
            <v-col cols="2">
              <hr class="rayita">
            </v-col>
            <v-col>
              <p>Have a presale question about our products and features? Or looking for a refund?</p>
            </v-col>
            <v-btn
            color="white"
            class="ma-2 "
            rounded
            outlined
            dark
            target="_blank"
            >
              <span class="text-lowercase">sales@salesemail.com</span>
            </v-btn>
          </v-col>
        </v-col>
      </v-row>
      <v-row justify="space-around" class="my-12" >
        <v-col  cols="2" v-for="k in 5"
        :key="k">
          <v-img
          height="40"
          contain
          :src="require( '../assets/clients/clients-logo'+k+'.png' ) " />
        </v-col>
      </v-row>
      <v-row >
        <v-col  cols="6">
          <v-row >
            <h3 class="display-1 font-weight-light">Start <span class="color-purple display-1 font-weight-black">growing</span> your bussiness.</h3>
            <p class="font-weight-light mt-8">Your issue is our main priority. Our 24/7 support team, is here to help you and make sure our product is up to date. Have a presale question about our products and features? Or looking for a refund? We would love to hear what you concern is. Online awards and publications.</p>
          </v-row >
        </v-col>
        <v-row justify="center" align="center">
          <v-col  cols="6">
            <v-btn
            color="#66cccc"
            class="ma-2 "
            rounded
            depressed
            dark
            large
            block
            height="8vh"
            target="_blank"
            >
              GET STARTED NOW!
            </v-btn>
          </v-col>
        </v-row>
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
  background-image: url('~@/assets/vector-footer.svg');
  background-repeat: no-repeat;
  background-attachment: scroll;
  background-position: bottom;
  background-size: cover;
}
hr.rayita{
  border: 0.5px solid  #66cccc;
}
.mail-resaltado hr.rayita{
  border: 0.5px solid  #fff;
}
.mail-resaltado{
  background-color: #66cccc;
  color: white
}
</style>
