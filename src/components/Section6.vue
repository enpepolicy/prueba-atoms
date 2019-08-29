<template lang="html">
  <v-container fill-height>
    <v-container>
      <v-row >
        <v-col  cols="5">
          <v-list>
            <v-list-item dense>
              <v-list-item-content>
                <h3 class="display-1 font-weight-black">Frequently asked questions</h3>
              </v-list-item-content>
            </v-list-item>
            <v-list-item dense>
              <v-list-item-content>
                <p class="font-weight-light">Have a presale question about our products and features? Or looking for a refund? We would love to hear what your concern is.</p>
              </v-list-item-content>
            </v-list-item>
            <v-list-item dense>
              <v-list-item-icon>
                <v-icon>mdi-check</v-icon>
              </v-list-item-icon>
              <v-list-item-content>
                <p>Simple and Smart HTML code</p>
              </v-list-item-content>
            </v-list-item>
            <v-list-item dense>
              <v-list-item-icon>
                <v-icon>mdi-check</v-icon>
              </v-list-item-icon>
              <v-list-item-content>
                <p>Works reintegrated in any part of the layout</p>
              </v-list-item-content>
            </v-list-item>
            <v-list-item dense>
              <v-list-item-icon>
                <v-icon>mdi-check</v-icon>
              </v-list-item-icon>
              <v-list-item-content>
                <p>Reuse these elements fro one desing to another</p>
              </v-list-item-content>
            </v-list-item>
          </v-list>
        </v-col>
        <v-col  cols="7">
          <v-expansion-panels accordion mandatory>
            <v-expansion-panel >
              <v-expansion-panel-header >Installing the app on all devices</v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel>
              <v-expansion-panel-header>How to implement and manage API key</v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel>
              <v-expansion-panel-header>How to set up and optimize your account</v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel>
              <v-expansion-panel-header>Manage your account acces and security settings</v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel>
              <v-expansion-panel-header>API integration basic overview</v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel>
              <v-expansion-panel-header>Deactivating or deleting your account</v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>
        </v-expansion-panels>
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
.v-expansion-panel--active .v-expansion-panel-header{
  background-color: #66cccc;
  color: white
}
.v-expansion-panel-content{
  padding-top: 16px
}
</style>
