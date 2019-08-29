<template lang="html">
    <v-toolbar flat color="transparent">
      <v-toolbar-title class="headline text-uppercase">
        <span class="font-weight-light">LATERAL</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        rounded
        text
        target="_blank"
        class="ma-4"
      >
        <span >Home</span>
      </v-btn>
      <v-btn
        rounded
        text
        target="_blank"
        class="ma-4"
      >
        <span >Features</span>

        <v-img
        class="ml-2"
        :src="require('../assets/drop-down.png')" />
      </v-btn>
      <v-btn
        rounded
        text
        target="_blank"
        class="ma-4"
      >
        <span >Pricing</span>
      </v-btn>
      <v-btn
        rounded
        text
        target="_blank"
        class="ma-4"
      >
        <span >Contact</span>
      </v-btn>
      <v-btn
        id="login"
        color="#66cccc"
        class="ma-4"
        rounded
        outlined
        text
        target="_blank"
      >
        <span>LOGIN</span>
      </v-btn>
      <v-btn
        class="ma-4"
        dark
        rounded
        outlined
        text
        target="_blank"
      >
        <span >GET STARTED</span>
      </v-btn>
    </v-toolbar>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
#login{
  border-color: #66cccc
}

</style>
