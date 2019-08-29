<template>
  <v-app>
    <v-container fluid>
      <Section1 class="fullH"/>
      <Section2 class="fullH"/>
      <Section3 class="fullH"/>
      <Section4 class="fullH"/>
      <Section5 class="fullH"/>
      <Section6 class="fullH"/>
      <Section7 class="fullH"/>
      <Footer />
    </v-container>
  </v-app>
</template>

<script>
import Footer from './components/Footer'
import Section1 from './components/Section1'
import Section2 from './components/Section2'
import Section3 from './components/Section3'
import Section4 from './components/Section4'
import Section5 from './components/Section5'
import Section6 from './components/Section6'
import Section7 from './components/Section7'

export default {
  name: 'App',
  components: {
    Footer,
    Section1,
    Section2,
    Section3,
    Section4,
    Section5,
    Section6,
    Section7
  },
  data: () => ({
    //
  }),
};
</script>

<style>
h1{
  font-size: 3em;
  font-weight: 600;
}
h2{
  font-size: 2.2em;
  font-weight: 600;
}
h3{
  font-size: 1.6em;
  font-weight: 200;
}
p{
  font-size: 1em
}
.texto-grande{
  font-size: 2em
}
.color-purple{
  color: #9966cc;
}
.color-blue{
  color: #66cccc;
}
.container--fluid{
  padding: 0
}
.fullH{
  min-height: 100vh
}
.v-tab{
  margin-bottom: 1.5em
}
#app{
  background-image: url('~@/assets/mascara-blanca.svg'), url('~@/assets/bg.jpg');
  z-index: 1, 2, 3;
  background-repeat: no-repeat;
  background-attachment: scroll, fixed;
  background-position: top, top;
  background-size:cover, auto;
}
</style>
