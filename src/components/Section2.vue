<template lang="html">
  <v-container fill-height>
    <v-container>
      <v-row justify="center"  >
        <v-col  cols="12">
          <h2 class="text-center">Features designed for you</h2>
        </v-col>
      </v-row>
      <v-row justify="center">
        <v-col cols="1">
          <hr>
        </v-col>
      </v-row>
      <v-row justify="center" >
        <v-col cols="6">
          <p class="text-center">We believe we have created the most efficient SaaS landing page for your users. Landing page with features that wil convince you to use it for your Saas business.</p>
        </v-col>
      </v-row>
      <v-row >
        <v-col cols="4">
          <v-col>
            <v-img
            class="align-start"
            height="60"
            max-width="60"
            contain
            :src="require('../assets/icons/responsive-64.png')" />
          </v-col>
          <v-col>
            <h3>Responsive <strong class="font-weight-black">Layout Template</strong></h3>
          </v-col>
          <v-col cols="2">
            <hr class="rayita">
          </v-col>
          <v-col>
            <p>Responsive code that makes your landing page look good on all devices (desktops, tablets, and phones). Created with mobile specialists.</p>
          </v-col>
        </v-col>
        <v-col cols="4">
          <v-col>
            <v-img
            class="align-start"
            height="60"
            max-width="60"
            contain
            :src="require('../assets/icons/desktop-chart-64.png')" />
          </v-col>
          <v-col>
            <h3><strong class="font-weight-black">SaaS Landing Page</strong> Analysis</h3>
          </v-col>
          <v-col cols="2">
            <hr class="rayita">
          </v-col>
          <v-col>
            <p>A perfect structure created after we analized trends in SaaS landing page designs. Analysis made to the most popular Saas businesses.</p>
          </v-col>
        </v-col>
        <v-col cols="4">
          <v-col>
            <v-img
            class="align-start"
            height="60"
            max-width="60"
            contain
            :src="require('../assets/icons/browser-64.png')" />
          </v-col>
          <v-col>
            <h3><strong class="font-weight-black">Smart </strong>Bem <strong class="font-weight-black">Grid</strong></h3>
          </v-col>
          <v-col cols="2">
            <hr class="rayita">
          </v-col>
          <v-col>
            <p>Blocks, Elements and Modifiers. A smart HTML/CSS structure that can easely be reused. Layout driven by the purpose of modularity.</p>
          </v-col>
        </v-col>
        <v-col cols="4">
          <v-col>
            <v-img
            class="align-start"
            height="60"
            max-width="60"
            contain
            :src="require('../assets/icons/desktop-windows-64.png')" />
          </v-col>
          <v-col>
            <h3><strong class="font-weight-black">Multiple </strong>Unique <strong class="font-weight-black">Designs</strong></h3>
          </v-col>
          <v-col cols="2">
            <hr class="rayita">
          </v-col>
          <v-col>
            <p>Choose between multiple unique designs and easy integrate elements from one design to another. Following the latest design trends.</p>
          </v-col>
        </v-col>
        <v-col cols="4">
          <v-col>
            <v-img
            class="align-start"
            height="60"
            max-width="60"
            contain
            :src="require('../assets/icons/customizer-64.png')" />
          </v-col>
          <v-col>
            <h3>Flexible <strong class="font-weight-black">HTML Sections </strong>Layout Template</h3>
          </v-col>
          <v-col cols="2">
            <hr class="rayita">
          </v-col>
          <v-col>
            <p>Simple and Smart Html code that works reintegrated in any part of the layout. Reuse the elements from one design to another.</p>
          </v-col>
        </v-col>
        <v-col cols="4">
          <v-col>
            <v-img
            class="align-start"
            height="60"
            max-width="60"
            contain
            :src="require('../assets/icons/users-64.png')" />
          </v-col>
          <v-col>
            <h3><strong class="font-weight-black">User </strong>Friendly</h3>
          </v-col>
          <v-col cols="2">
            <hr class="rayita">
          </v-col>
          <v-col>
            <p>Easy to navigate. Made with user experience in mind, in order to provide the perfect landing page experience for your client.</p>
          </v-col>
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
hr.rayita{
  border: 0.5px solid #9966cc;
}
</style>
