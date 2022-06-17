<template>
    <div class="container-fluid bg">
        <div class="row justify-content-between align-items-center">
            <div class="col-2">
                <img class="logo mt-3" :src="require('../assets/img/gym_logo_2x.png')" alt="">

            </div>
            <nav class="col-5 nav">
                <ul class="nav" v-for="(voice, index) in avadaMenu" :key="index">
                    <li class="nav-item"><a class="nav-link" href="#">{{voice}}</a></li>
                </ul>
            </nav>
        </div>
        <div class="container">
        </div>
        <div class="row text-center align-self-center">
            <div class="col-12">
                <h1 class="">NO PAIN NO GAIN</h1>

            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'AvadaHeader',
  props: {
    msg: String
  },
  data () {
    return {
        avadaMenu:["HOME", "ABOUT US", "FACILITIES", "MEMBERSHIP", "TESTIMONIALS"],
    }

  }  
}
</script>

<!-- HOME ABOUT US FACILITIES MEMBERSHIP TESTIMONIALS -->

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

// PALETTE
// color cube
$shark: #252a2d;
$chestNut: #d5635f;
$doveGray: #6b6b6b;
$edward: #aeafae;
$white: #fafafa;
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

img {
    max-width: 100%;
}
.bg {
    height: 100vh;
    background-position: top;
    background-repeat: no-repeat;
    background-size: cover;
    background-image: url('@/assets/img/home-banner.jpg');
}

h1 {
    font-weight: 700;
    font-size: 5rem;
}
li.nav-item {
    font-size: 0.7rem;

}

a.nav-link {
    color: #aeafae;
}
</style>
