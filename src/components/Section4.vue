<template lang="html">
  <v-container fill-height>
    <v-container>
      <v-row justify="center"  >
        <v-col  cols="12">
          <h2 class="text-center">Flexible Pricing</h2>
        </v-col>
      </v-row>
      <v-row justify="center">
        <v-col cols="1">
          <hr>
        </v-col>
      </v-row>
      <v-row justify="center" >
        <v-col cols="6">
          <p class="text-center">We believe created the most efficient Saas landing page for your users. Landing page with features that will convince you to use it for your SaaS business.</p>
        </v-col>
      </v-row>
      <v-row justify="center">
        <v-col cols="4">
          <v-tabs
            v-model="tab"
            centered
            background-color="transparent"
            slider-color="#9966cc"
            color="black"
            class="mt-5"
            >
            <v-tab >
              Monthly
            </v-tab>
            <v-tab>
              Yearly
            </v-tab>
          </v-tabs>
        </v-col>
      </v-row>
      <v-row justify="center" align="center">
        <v-col cols="3">
          <v-tabs-items v-model="tab">
            <v-tab-item>
              <v-row justify="center">
                <h3 class="oferta">FREE</h3>
              </v-row>
              <v-row justify="center">
                <v-col cols="3">
                  <hr>
                </v-col>
              </v-row>
              <v-row justify="center">
                <p class="price">$<span class="big-number">0</span> /month</p>
              </v-row>
              <v-list>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p><strong>1</strong> User Account</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p><strong>10</strong> Team Members</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p><strong>Unlimited</strong> Emails Accounts</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p>Set And Manage Permissions</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p class="tachar">API & extension support</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p class="tachar">Developers Support</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p class="tachar">A/B Testig</p>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
              <div class="text-center">
                <v-btn
                id="login"
                color="#66cccc"
                class="ma-2 "
                rounded
                large
                outlined
                dark
                target="_blank"
                >
                  <span>Sign up</span>
                </v-btn>
              </div>
            </v-tab-item>
          </v-tabs-items>
        </v-col>
        <v-col cols="3">
          <v-tabs-items v-model="tab">
            <v-tab-item>
              <v-row justify="center">
                <h3 class="oferta">STARTUP</h3>
              </v-row>
              <v-row justify="center">
                <v-col cols="3">
                  <hr>
                </v-col>
              </v-row>
              <v-row justify="center">
                <p class="price">$<span class="big-number">29</span> /month</p>
              </v-row>
              <v-list>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p><strong>10</strong> User Accounthola</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p><strong>100</strong> Team Members</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p><strong>Unlimited</strong> Emails Accounts</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p>Set And Manage Permissions</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p>API & extension support</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p class="tachar">Developers Support</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p class="tachar">A/B Testig</p>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
              <div class="text-center">
                <v-btn
                id="login"
                color="#66cccc"
                class="ma-2 "
                rounded
                large
                outlined
                dark
                target="_blank"
                >
                  <span>Sign up</span>
                </v-btn>
              </div>
            </v-tab-item>
          </v-tabs-items>
        </v-col>
        <v-col cols="3">
          <v-tabs-items v-model="tab">
            <v-tab-item>
              <v-card
              color="#9966cc"
              elevation="10">
              <v-row justify="center">
                <h3 class="oferta white--text pro">PRO</h3>
              </v-row>
              <v-row justify="center">
                <v-col cols="3">
                  <hr>
                </v-col>
              </v-row>
              <v-row justify="center">
                <p class="white--text">$<span class="big-number">49</span> /month</p>
              </v-row>
              <v-list color="#9966cc">
                <v-list-item dense dark>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p><strong>50</strong> User Accounthola</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense dark>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p><strong>500</strong> Team Members</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense dark>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p><strong>Unlimited</strong> Emails Accounts</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense dark>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p>Set And Manage Permissions</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense dark>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p>API & extension support</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense dark>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p>Developers Support</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense dark>
                  <v-list-item-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p class="tachar">A/B Testig</p>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
              <div class="text-center">
                <v-btn
                id="login"
                color="#66cccc"
                class="ma-2 "
                rounded
                dark
                large
                target="_blank"
                >
                  <span>Sign up</span>
                </v-btn>
              </div>
              </v-card>
            </v-tab-item>
          </v-tabs-items>
        </v-col>
        <v-col cols="3">
          <v-tabs-items v-model="tab">
            <v-tab-item>
              <v-row justify="center">
                <h3 class="oferta">ULTRA</h3>
              </v-row>
              <v-row justify="center">
                <v-col cols="3">
                  <hr>
                </v-col>
              </v-row>
              <v-row justify="center">
                <p class="price">$<span class="big-number">99</span> /month</p>
              </v-row>
              <v-list>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p><strong>Unlimited</strong> User Accounthola</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p><strong>Unlimited</strong> Team Members</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p><strong>Unlimited</strong> Emails Accounts</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p>Set And Manage Permissions</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p>API & extension support</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                    <v-icon>mdi-check</v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p>Developers Support</p>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item dense>
                  <v-list-item-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <p>A/B Testig</p>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
              <div class="text-center">
                <v-btn
                id="login"
                color="#66cccc"
                class="ma-2 "
                rounded
                large
                outlined
                dark
                target="_blank"
                >
                  <span>Sign up</span>
                </v-btn>
              </div>
            </v-tab-item>
          </v-tabs-items>
        </v-col>
      </v-row>
    </v-container>
  </v-container>
</template>

<script>
  export default {
    data () {
      return {
        tab: null
      }
    },
  }
</script>

<style lang="css" scoped>
.oferta{
  font-weight: 700;
}
.price{
  font-weight: 700;
}
.big-number{
  font-size: 3em;
}
.tachar{
  text-decoration:line-through;
  font-weight: 100
}
.v-application p{
  margin-bottom: 0;
}
.v-card{
  padding: 1em;
}
.pro{
  font-size: 2.4em
}

</style>
