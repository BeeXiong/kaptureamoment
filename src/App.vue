<template>
  <div id="app">
    <app-navbar></app-navbar>
    <app-body></app-body>
  </div>
</template>

<script>
import AboutUs from './components/AboutUs.vue'
import Navbar from './components/Navbar.vue'

export default {
  name: 'app',
  components: {
    'app-navbar': Navbar,
    'app-body' : AboutUs
  }
}
</script>

<style lang="scss">
h1 { font-family: Candara }
h2 { font-family: Candara }
h3 { font-family: Candara }
h4 { font-family: Candara }
h5 { font-family: Candara }
p { font-family: Candara}

@media(max-height: 800px){
  body{
    /* background: linear-gradient(90deg, #ffffff 65%, #2b2926 35%) no-repeat; */
    background: none;
    padding-top: 75px;
  }

}
@media(min-width : 801px) and (max-width : 1149px) {
  body{
    background: none;
    padding-top: 75px;
  }

}
@media(min-width : 1150px) {
  body{
    background: linear-gradient(90deg, #2b2926 35%, #ffffff 0% ) no-repeat;
    padding-top: 75px;
  }
}
</style>
