<template>
  <div id="app">
    <AvadaHeader>
    </AvadaHeader>
    <main>
      <div class="container">
        <div class="row">
          <div class="col-4">
            <img src="https://via.placeholder.com/150" alt="">
          </div>
          <div class="col-4">
            <img src="https://via.placeholder.com/150" alt="">
          </div>
          <div class="col-4">
            <img src="https://via.placeholder.com/150" alt="">
          </div>

        </div>
      </div>

    </main>

    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<!-- header top trasparente (logo + menu) dati HOME ABOUT US FACILITIES MEMBERSHIP TESTIMONIALS BLOG -->
<!-- SPLASH img home-banner.jpg ; NO PAIN NO GAIN centrato poi testo e pulsante-->
<!-- title WORLD CLASS con triangolino in relative? -->
<!-- form iscrizione al tarining -->
<!-- section con background e 4 oggettini (icone? non ci sono) forza e trattamento, muov ecardio, flessibilità e riposo, salute e dieta -->
<!-- REAL WORLD RESULTS section con 4 figure e le loro cit; stessa sec HIGH PERFORMANCE FACILITIES con 6 foto greyscale -->
<!-- altra section con bg pugnazzi e frase Bruce Lee -->
<!-- sec MEET OUR TRAINER 3 schede con foto, testo e iconcine social, tasto per svelarne altri (js?); altro triangolino -->
<!-- PERFORMANCE NEWS schete foto e testo non affiancate; tasto READ ALL ARTICLES -->
<!-- sez Achieve Your Fitness Goals; titolo + p e tasto sfondo "parallasse" ?? -->
<!-- footer 3 menu + foto -->
<!-- bottom-bar stringa copyright + social + tasto per tornar su -->

<script>
import AvadaHeader from './components/AvadaHeader.vue'
undefined

export default {
  name: 'App',
  components: {
    // HelloWorld,
    AvadaHeader
},
  data () {
    return {
    }

  }
}
</script>

<style lang="scss">

// PALETTE
// color cube
$shark: #252a2d;
$chestNut: #d5635f;
$doveGray: #6b6b6b;
$edward: #aeafae;
$hockeyPokey: #d8bc29;
// median cut
$sharkM: #212425;
$oldRose: #c88a80;
$pineCone: #70625b;
$oldGray: #899696;
$regentGray: #7e8995;
// material design
$chestNutRose: #d3615e;
$trarch: #b4a394;
$irishCoffee: #632927;
$woodSmoke: #070809;
$antiqueBrass: #c2856c;

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: $chestNut;
  margin-top: 60px;
}

</style>
