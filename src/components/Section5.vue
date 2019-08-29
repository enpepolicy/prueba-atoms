<template lang="html">
  <v-container fluid fill-height>
    <v-container >
      <v-row justify="center"  >
        <v-col  cols="12">
          <h2 class="text-center">Trusted by world experts</h2>
        </v-col>
      </v-row>
      <v-row justify="center">
        <v-col cols="1">
          <hr>
        </v-col>
      </v-row>

      <v-row
      class="mt-8"
        v-for="item in justify"
        :key="item.j"
        :justify="item.j"
      >
        <v-col
          v-for="k in 3"
          :key="k"
          md="2"
          align="center"
        >
          <v-img
          contain
          :width="Math.floor(Math.random() * 10) * 15"
          :src="require( '../assets/avatar-'+k+'.jpg' ) " />
        </v-col>
      </v-row>
    </v-container>
  </v-container>
</template>

<script>
  export default {
    data: () => ({
      justify: [
        {
          j:'start'
        },
        {
          j:'space-around'
        },
        {
          j:'end'
        },
        {
          j:'space-between'
        }
      ],
    }),
  }
</script>

<style lang="css" scoped>
.container--fluid{
  background-image: url('~@/assets/world-bg.png');
  background-repeat: no-repeat;
  background-attachment: scroll;
  background-position: top;
  background-size: auto 100%;
  background-color: #f7f8fa;
}
.v-image{
  border-radius: 50%;
  border: 0.5em solid #f1f2f4;
  border-style: double;
}
</style>
