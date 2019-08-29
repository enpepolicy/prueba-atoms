<template lang="html">
  <v-container fluid fill-height>
    <v-container >
      <v-row justify="center">
        <v-col  cols="12">
          <h2 class="text-center">Easy to use API</h2>
        </v-col>
      </v-row>
      <v-row justify="center">
        <v-col cols="1">
          <hr>
        </v-col>
      </v-row>
      <v-row justify="center" >
        <v-col cols="6">
          <p class="text-center">Guide to setup and configuration. You can present below a guide and a description of how your system configurationworks and add some animated screens.</p>
        </v-col>
      </v-row>
      <v-row justify="center">
        <v-col cols="12">
          <v-tabs
            v-model="tab"
            right
            background-color="transparent"
            slider-color="#9966cc"
            color="black"
            >
            <v-tab >
              Initializing JS
            </v-tab>
            <v-tab>
              Configuration CSS
            </v-tab>
            <v-tab>
              Security Levels API
            </v-tab>
          </v-tabs>
          <hr>
          <v-tabs-items v-model="tab">
            <v-tab-item>
              <code>
                function Persona(){
                  this.edad = 0;

                  setInterval(() => {
                    this.edad++; // |this| apunta al objeto Persona
                  }, 1000);
                }

                var p = new Persona();
              </code>
            </v-tab-item>
            <v-tab-item>
              <code>
                var adder = {
                  base : 1,

                  add : function(a) {
                    var f = v => v + this.base;
                    return f(a);
                  },

                  addThruCall: function(a) {
                    var f = v => v + this.base;
                    var b = {
                      base : 2
                    };

                    return f.call(b, a);
                  }
                };

                console.log(adder.add(1));         // Imprime 2 como es esperado
                console.log(adder.addThruCall(1)); // También imprime 2 aunque se esperaba 3
              </code>
            </v-tab-item>
            <v-tab-item>
              <code>
                function Persona(){
                  this.edad = 0;

                  setInterval(() => {
                    this.edad++; // |this| apunta al objeto Persona
                  }, 1000);
                }

                var p = new Persona()
              </code>
            </v-tab-item>
          </v-tabs-items>
          <div class="text-end botones">
            <v-btn
            id="login"
            color="#66cccc"
            depressed
            dark
            class="ma-2"
            rounded
            target="_blank"
            >
              <span>GET THE CODE</span>
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
              <span>RUN EXAMPLE</span>
            </v-btn>
          </div>
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
.container{
  background-color: #f7f8fa;
}
.v-window-item{
  margin-top: 2em;
}
.botones{
  background-color: #cfccd3;
  padding: 1em;
}
.v-application code{
  border-radius: 0;
  width: auto;
  background-color: white;
  box-shadow: none;
  -webkit-box-shadow: none;
  margin: 1em
}
</style>
