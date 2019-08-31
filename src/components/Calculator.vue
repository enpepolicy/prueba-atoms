<template lang="html">
  <v-card >
    <h3 class="text-center font-weight-bold pt-8">Credit Calculator</h3>
    <v-row justify="center">
      <v-col cols="2">
        <hr class="rayita">
      </v-col>
    </v-row>
    <v-row justify="center" class="">
      <v-col cols="10" class="pb-0">
        <h3 class="text-end font-weight-bold title">Desired amount</h3>
      </v-col>
    </v-row>
    <v-row justify="center" class="">
      <v-col cols="10">
        <vue-slider
        v-model="deseado"
        :min="10000"
        :interval="1000"
        :max="1000000"
        :tooltip-formatter="formatter1"
        :tooltip="'always'"
        />
      </v-col>
    </v-row>
    <v-row justify="center" >
      <v-col cols="10" class="pb-0">
        <h3 class="text-end font-weight-bold title">Anual rate</h3>
      </v-col>
    </v-row>
    <v-row justify="center" class="">
      <v-col cols="10">
        <VueSlider
        v-model="tasaAnual"
        :min="8.9"
        :interval="0.1"
        :max="100"
        :tooltip-formatter="formatter2"
        :tooltip="'always'"
        />
      </v-col>
    </v-row>
    <v-row justify="center" >
      <v-col cols="10">
        <hr class="rayita-gris ">
      </v-col>
    </v-row>
    <v-row>
      <v-col >
        <h3 class="text-center font-weight-bold">Term in months</h3>
      </v-col>
    </v-row>
    <v-row justify="center" >
      <v-col class="text-center" cols="3">
        <v-btn
        ref="focus"
        @click="meses = 12"
        outlined
        color="#9966cc"
        fab>12</v-btn>
      </v-col >
      <v-col class="text-center" cols="3">
        <v-btn
        @click="meses = 24"
        value="4"
        outlined
        color="#9966cc"
        fab
        >24</v-btn>
      </v-col>
      <v-col class="text-center" cols="3">
        <v-btn
        @click="meses = 36"
        outlined
        color="#9966cc"
        fab>36</v-btn>
      </v-col>
    </v-row>
    <v-row justify="center" >
      <v-col cols="10">
        <hr class="rayita-gris ">
      </v-col>
    </v-row>
    <v-row justify="center" align="center">
      <v-col cols="6">
        <p class="text-end font-weight-light">Monthly payment</p>
      </v-col>
      <v-col cols="6">
        <p class="datos">
          $ {{((deseado/meses)+(deseado*tasaAnual/1200)).toLocaleString('en', {minimumFractionDigits: 2, maximumFractionDigits: 2})}}
        </p>
      </v-col>
    </v-row>
    <v-row justify="center" align="center">
      <v-col cols="6">
        <p class="text-end font-weight-light">Opening comission</p>
      </v-col>
      <v-col cols="6">
        <p class="datos">
          $ {{(apertura).toLocaleString('en', {minimumFractionDigits: 2, maximumFractionDigits: 2})}}
        </p>
      </v-col>
    </v-row>
    <v-row justify="center" align="center">
      <v-col cols="6">
        <p class="text-end font-weight-light">Net amount deposited</p>
      </v-col>
      <v-col cols="6">
        <p class="datos">
          $ {{(deseado-apertura).toLocaleString('en', {minimumFractionDigits: 2, maximumFractionDigits: 2})}}
        </p>
      </v-col>
    </v-row>
    <v-row justify="center" align="center">
      <v-col cols="6">
        <p class="text-end font-weight-light">Payed Total</p>
      </v-col>
      <v-col cols="6">
        <p class="datos">
          $ {{((((deseado/meses)+(deseado*tasaAnual/1200))*(meses))+apertura).toLocaleString('en', {minimumFractionDigits: 2, maximumFractionDigits: 2})}}
        </p>
      </v-col>
    </v-row>
    <v-row justify="center" align="center">
      <v-col cols="6">
        <p class="text-end font-weight-light">CAT</p>
      </v-col>
      <v-col cols="6">
        <p class="datos">
          {{cat}} %
        </p>
      </v-col>
    </v-row>
    <v-row justify="center" align="center" >
      <v-col cols="7" class="text-center mb-4" >
        <v-btn
        color="#9966cc"
        class="ma-2"
        block
        rounded
        depressed
        dark
        target="_blank"
        >
          <span>SOLICITAR MI CREDITO</span>
        </v-btn>
      </v-col >
    </v-row>
  </v-card>
</template>

<script>
import VueSlider from 'vue-slider-component'
export default {
  components: {
    VueSlider
  },
  data: function () {
    return {
      meses: 12,
      deseado: 10000,
      tasaAnual: 8.9,
      apertura: 348,
      pagoMensual: 0,
      cat: 15.71,
      formatter1: v => `${(v + '').replace(/\B(?=(\d{3})+(?!\d))/g, '.')}`,
      formatter2: v => `${(v + '').replace(/\B(?=(\d{3})+(?!\d))/g, '.')}%`,
    }
  },
  mounted: function () {
    this.$refs.focus.$el.focus()
  }
}
</script>

<style lang="scss" scoped >
@import '../assets/slider.css';
.v-application p{
  margin-bottom: 0;
}
.datos{
  border-radius: 2em;
  border:1px solid black;
  width: 10em;
  text-align: center;
  padding: 0.4em
}
.v-btn:focus{
  background-color: #9966cc;
  color: white !important;
}
hr.rayita{
  border: 0.5px solid black;
}
hr.rayita-gris{
  border: 0.5px solid #f0e8f7;
}
</style>
