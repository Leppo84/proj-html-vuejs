<template>
    <div class="bg">
        <div class="nav-wrapper container-fluid">
            <div class="row justify-content-between align-items-center align-content-center text-center">
                <div class="col-2 m-4 ml-5">
                    <img class="logo" :src="require('../assets/img/gym_logo_2x.png')" alt="">
                </div>
                <nav class="col-5 nav flex-nowrap ">
                    <ul class="list-inline" v-for="(voice, index) in avadaMenu" :key="index">
                        <li class="nav-item"><a class="nav-link" :id="`menu-item-${index}`" href="#">{{voice}}</a></li>
                    </ul>
                </nav>
            </div>
        </div>
        <div class="container">
            <div class="row splash text-center align-items-center">
                <div class="col-12">
                    <h1 class="thick">NO PAIN NO GAIN</h1>
                    <span>
                        Motivation is what gets you started. Habits is what keeps you going.
                    </span>
                    <br>
                    <button> JOIN US TODAY</button>
                </div>
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
        avadaMenu:["HOME", "ABOUT US", "FACILITIES", "MEMBERSHIP", "TESTIMONIALS", "BLOG"],
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

// div.nav-wrapper {
//     width:95%;
//     margin: auto;
// }

img {
    max-width: 80%;
}
.bg {
    height: 100vh;
    background-position: 0px -30px;
    background-repeat: no-repeat;
    background-size: cover;
    background-image: url('@/assets/img/home-banner.jpg');
}

h1.thick {
    font-weight: 700;
    font-size: 4rem;
}
li.nav-item {
    font-size: 0.5rem;

}

a.nav-link {
    color: #aeafae;
}

#menu-item-0 {
    color: #d3615e;
}

.splash {
    height: 60vh;
}
</style>
