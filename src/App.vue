<template>
  <div id="app">
    <AvadaHeader/>
    <main>
      <!-- Presentation -->
      <section class="bg-basegrey">
        <div class="container-fluid">
          <div class="row text-center justify-content-center">
            <div class="col-7 m-5">
              <br>
              <h4 class="thick">
                  WORLD CLASS Fitness
              </h4>
              <img class="m-2" :src="require('./assets/img/divider-xx-red.png')" alt="Divider">
              <br>
              <p>
                At Avada gym, everithng we do from top to bottom is of the highest quality to ensure we're equipped to help you reach your goals of a healthy and fit life style.
              </p>
              <br>
            </div>
          </div>
        </div>
      </section>
      <!-- here comes the triangle -->
      <!-- form section -->
      <section class="bg-mediumgrey">
        <div class="container-fluid">
          <div class="row justify-content-center">
              <div class="col-7">
                <div class="row justify-content-center pt-5 pb-5 mt-5 mb-5">
                  <div class="col-6">
                    <img :src="require('./assets/img/home_img-compressor.jpg')" alt="">
                  </div>
                  <div class="col-6">
                    <h6 class="thick small">
                      Sign Up For A Training Session!
                    </h6>
                    <label class="small txtgrey mt-3" for="input-name">Name:</label>
                    <input type="text" id="input-name">
                    <br>
                    <label class="small txtgrey mt-3" for="input-mail">Email:</label>
                    <input type="email" name="" id="input-mail">
                    <br>
                    <button class="btn-form mt-3 p-2">START NOW!</button>
                  </div>
                </div>
                
              </div>
          </div>
        </div>
      </section>
      <!-- first bg break (training icons) -->
      <section class="bg-gym">
        <div class="container-fluid">
          <div class="row justify-content-center pt-5 pb-5">
            <div class="col-7">
              <div class="row text-center mt-5 mb-5">
                <div class="col-3">
                  <img class="icon" :src="require('./assets/img/Strenght.svg')" alt="">
                  <h6 class="thick small mt-3">
                    Strnght & Conditioning
                  </h6>
                   <img class="m-2" :src="require('./assets/img/divider-x-red.png')">
                  <p class="grey-txt" >Lorem ipsum dolor sit amet consectetur adipisicing elit. In augue nisl, ornare es volutpat etra us.</p>
                </div>
                <div class="col-3">
                  <img class="icon" :src="require('./assets/img/Fitness.svg')" alt="Divider">
                  <h6 class="thick small mt-3">
                    Strnght & Conditioning
                  </h6>
                   <img class="m-2" :src="require('./assets/img/divider-x-red.png')">
                  <p class="grey-txt" >Lorem ipsum dolor sit amet consectetur adipisicing elit. In augue nisl, ornare es volutpat etra us.</p>
                </div>
                <div class="col-3">
                  <img class="icon" :src="require('./assets/img/Flex.svg')" alt="">
                  <h6 class="thick small mt-3">
                    Strnght & Conditioning
                  </h6>
                   <img class="m-2" :src="require('./assets/img/divider-x-red.png')">
                  <p class="grey-txt" >Lorem ipsum dolor sit amet consectetur adipisicing elit. In augue nisl, ornare es volutpat etra us.</p>
                </div>
                <div class="col-3">
                  <img class="icon" :src="require('./assets/img/Diet.svg')" alt="">
                  <h6 class="thick small mt-3">
                    Strnght & Conditioning
                  </h6>
                   <img class="m-2" :src="require('./assets/img/divider-x-red.png')">
                  <p class="grey-txt" >Lorem ipsum dolor sit amet consectetur adipisicing elit. In augue nisl, ornare es volutpat etra us.</p>
                </div>
              </div>
            </div>
           </div>
        </div>
      </section>
      <!-- Reviews & facilities -->
      <section class="bg-basegrey">
        <div class="container-fluid">
          <div class="row text-center justify-content-center">
            <div class="col-7 m-5">
              <br>
              <h4 class="thick">
                  REAL WORLD RESULTS
              </h4>
              <img class="m-3" :src="require('./assets/img/divider-xx-red.png')" alt="Divider">
              <br>
              <div class="row justify-content-center text-start mb-4 mt-3">
                <div class="col-6 p-3">
                  <div class="col-12 bg-mediumgrey p-3">
                    <div class="row">
                      <div class="col-4">
                          <img :src="require('./assets/img/review_1-compressor.jpg')" alt="">
                      </div>
                      <div class="col-8 small">
                        <i>
                          "The trainers at Avada Gym have helied me reach mu fitness goals beyond anything I could of hoped for. I love it!"
                        </i>
                        <br>
                        <span>- Tara Smith
                        </span>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-6 p-3">
                  <div class="col-12 bg-mediumgrey p-3">
                    <div class="row">
                      <div class="col-4">
                          <img :src="require('./assets/img/review_1-compressor.jpg')" alt="">
                      </div>
                      <div class="col-8">
                        <p>
                          "The trainers at Avada Gym have helped me reach mu fitness goals beyond anything I could of hoped for. I love it!"
                        </p>
                        <span>
                          - Tara Smith
                        </span>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-6 p-3">
                  <div class="col-12 bg-mediumgrey p-3">
                    <div class="row">
                      <div class="col-4">
                          <img :src="require('./assets/img/review_1-compressor.jpg')" alt="">
                      </div>
                      <div class="col-8">
                        <p>
                          "The trainers at Avada Gym have helped me reach mu fitness goals beyond anything I could of hoped for. I love it!"
                        </p>
                        <span>
                          - Tara Smith
                        </span>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-6 p-3">
                  <div class="col-12 bg-mediumgrey p-3">
                    <div class="row">
                      <div class="col-4">
                          <img :src="require('./assets/img/review_1-compressor.jpg')" alt="">
                      </div>
                      <div class="col-8">
                        <p>
                          "The trainers at Avada Gym have helped me reach mu fitness goals beyond anything I could of hoped for. I love it!"
                        </p>
                        <span>
                          - Tara Smith
                        </span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <br>
              <h4 class="thick mt-5">
                  HIGH PERFORMANCE FACILITIES
              </h4>
              <img class="m-3" :src="require('./assets/img/divider-xx-red.png')" alt="Divider">
              <br>
              <div class="row justify-content-center">
                <div class="col-4">
                  <img :src="require('./assets/img/home-image1.jpg')" alt="">
                </div>
                <div class="col-4">
                  <img :src="require('./assets/img/home-image2.jpg')" alt="">
                </div>
                <div class="col-4">
                  <img :src="require('./assets/img/home-image3.jpg')" alt="">
                </div>
              </div>
              <div class="row justify-content-center mt-4 mb-5">
                <div class="col-4">
                  <img :src="require('./assets/img/home-image4.jpg')" alt="">
                </div>
                <div class="col-4">
                  <img :src="require('./assets/img/home-image54.jpg')" alt="">
                </div>
                <div class="col-4">
                  <img :src="require('./assets/img/home-image6.jpg')" alt="">
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- second bg break (fists quotes) -->
      <section class="bg-fists">
        <div class="container">
          <div class="row justify-content-center text-center">
            <div class="col-5 mt-4 mb-3">
                <p class="large mt-5">
                  <b class="half-thick mt-4">
                    "I fear not the man who has practiced 10,000 kicks once, but I fear the man who has practiced one kick 10,000 times"
                  </b>
                </p>
                <img class="m-3" :src="require('./assets/img/divider-white-xx.png')" alt="Divider">
                <br>
                <span class="thick my-3">BRUCE LEE - QUOTE OF THE DAY</span>
            </div>
           </div>
        </div>
      </section>
      <!-- Trainers presentation -->
      <section class="bg-mediumgrey">
        <div class="container-fluid">
          <div class="row text-center justify-content-center">
            <div class="col-7 m-5">
              <br>
              <h4 class="thick">
                  MEET OUR TRAINER
              </h4>
              <img class="m-2" :src="require('./assets/img/divider-xx-red.png')" alt="Divider">
              <br>
              <div class="row justify-content-center text-start">
                <div class="col-4 p-3">
                  <div class=" bg-basegrey p-0">
                    <img :src="require('./assets/img/trainer1.jpg')" alt="">
                    <div class="p-3">
                      <h6 class="small thick">
                        Ann Baker
                        <br>
                        Personal Trainer
                      </h6>
                      <p class="small txtgrey">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. In augue nisl, onare volutpal.
                      </p>
                      <br>
                        <div class="social-square col-2">
                          <img :src="require('./assets/img/soc-facebook.svg')" alt="">
                        </div>
                        <div class="social-square col-2">
                          <img :src="require('./assets/img/soc-twitter.svg')" alt="">
                        </div>
                        <div class="social-square col-2">
                          <img :src="require('./assets/img/soc-instagram.svg')" alt="">
                        </div>                                        
                    </div>
                  </div>
                </div>
                <div class="col-4 p-3">
                  <div class=" bg-basegrey p-0">
                    <img :src="require('./assets/img/trainer3.jpg')" alt="">
                    <div class="p-4">
                      <h6 class="small thick">
                        Ann Baker
                        <br>
                        Personal Trainer
                      </h6>
                      <p class="small txtgrey">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. In augue nisl, onare volutpal.
                      </p>
                      <br>
                        <div class="social-square col-2">
                          <img :src="require('./assets/img/soc-facebook.svg')" alt="">
                        </div>
                        <div class="social-square col-2">
                          <img :src="require('./assets/img/soc-twitter.svg')" alt="">
                        </div>
                        <div class="social-square col-2">
                          <img :src="require('./assets/img/soc-instagram.svg')" alt="">
                        </div>                                        
                    </div>
                  </div>
                </div>
                <div class="col-4 p-3">
                  <div class=" bg-basegrey p-0">
                    <img :src="require('./assets/img/trainer4.jpg')" alt="">
                    <div class="p-4">
                      <h6 class="small thick">
                        Ann Baker
                        <br>
                        Personal Trainer
                      </h6>
                      <p class="small txtgrey">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. In augue nisl, onare volutpal.
                      </p>
                      <br>
                        <div class="social-square col-2">
                          <img :src="require('./assets/img/soc-facebook.svg')" alt="">
                        </div>
                        <div class="social-square col-2">
                          <img :src="require('./assets/img/soc-twitter.svg')" alt="">
                        </div>
                        <div class="social-square col-2">
                          <img :src="require('./assets/img/soc-instagram.svg')" alt="">
                        </div>                                        
                    </div>
                  </div>
                </div>
              </div>
              <br>
              <button class="btn-trasp">VIEW ALL TRAINERS</button>
            </div>
          </div>
        </div>
      </section>
      <!-- second triangle -->
      <!-- Articles & News-->
      <section class="bg-basegrey">
        <div class="container-fluid">
          <div class="row text-center justify-content-center">
            <div class="col-7 m-5">
              <br>
              <h4 class="thick">
                  PERFORMANCE NEWS
              </h4>
              <img class="m-2" :src="require('./assets/img/divider-xx-red.png')" alt="Divider">
              <br>
              <div class="row justify-content-center text-start">
                <div class="col-4 p-3">
                  <div class=" bg-mediumgrey p-0">
                    <img :src="require('./assets/img/blog1.jpg')" alt="">
                    <div class="p-3">
                      <h6 class="small thick">
                        Train with free weights or your body weight?
                      </h6>
                      <p class="small txtgrey">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. In augue nisl, onare volutpal.
                      </p>                                       
                    </div>
                  </div>
                  <div class=" bg-mediumgrey p-0 mt-4">
                    <img :src="require('./assets/img/blog4.jpg')" alt="">
                    <div class="p-3">
                      <h6 class="small thick">
                        To be number one, train like you're number two
                      </h6>
                      <p class="small txtgrey">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. In augue nisl, onare volutpal.
                      </p>                                       
                    </div>
                  </div>
                </div>
                <div class="col-4 p-3">
                  <div class=" bg-mediumgrey p-0">
                    <img :src="require('./assets/img/blog6.jpg')" alt="">
                    <div class="p-3">
                      <h6 class="small thick">
                        Nutritional advice that will keep you training
                      </h6>
                      <p class="small txtgrey">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. In augue nisl, onare volutpal.
                      </p>
                    </div>
                  </div>
                  <div class=" bg-mediumgrey p-0 mt-4">
                    <img :src="require('./assets/img/trainer3.jpg')" alt="">
                    <div class="p-3">
                      <h6 class="small thick">
                        Top 5 mistakes every gym member makes
                      </h6>
                      <p class="small txtgrey">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. In augue nisl, onare volutpal.
                      </p>
                    </div>
                  </div>
                </div>
                <div class="col-4 p-3">
                  <div class=" bg-mediumgrey p-0">
                    <img :src="require('./assets/img/trainer4.jpg')" alt="">
                    <div class="p-3">
                      <h6 class="small thick">
                        Simple principles for your next workout
                      </h6>
                      <p class="small txtgrey">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. In augue nisl, onare volutpal.
                      </p>
                    </div>
                  </div>
                  <div class=" bg-mediumgrey p-0 mt-4">
                    <img :src="require('./assets/img/trainer1.jpg')" alt="">
                    <div class="p-3">
                      <h6 class="small thick">
                        The myths of shedding body fat explored
                      </h6>
                      <p class="small txtgrey">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. In augue nisl, onare volutpal.
                      </p>
                    </div>
                  </div>                  
                </div>
              </div>
              <br>
              <button class="btn-trasp">READ ALL ARTICLES</button>
            </div>
          </div>
        </div>
      </section>
      <!-- banner parallax -->
      <section class="bg-banner">
        <div class="container-fluid">
          <div class="row justify-content-center">
            <div class="col-7 my-5">
              <div class="row justify-content-between align-items-center">
                <div class="col-9">
                  <h5 class="thick">
                    Achieve Your Fitness Goals
                  </h5>  
                  <span class="thick small" >Flexible membership packages to suit all levels of athlete and achieve your fitness goals</span>
                </div>
                <div class="col-3 text-end">
                  <button class="btn-trasp" >JOIN US!</button>
               </div>
              </div>
           </div>
          </div>
        </div>
      </section>
    </main>
    <FooterAvada/>
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<!-- header top trasparente (logo + menu) dati HOME ABOUT US FACILITIES MEMBERSHIP TESTIMONIALS BLOG -->
<!-- SPLASH img home-banner.jpg ; NO PAIN NO GAIN centrato poi testo e pulsante-->
<!-- title WORLD CLASS con triangolino in relative? -->
<!-- form iscrizione al tarining -->
<!-- section con background e 4 oggettini (icone? non ci sono) forza e trattamento, muov ecardio, flessibilità e riposo, salute e dieta -->
<!-- REAL WORLD RESULTS section con 4 figure e le loro cit; stessa sec HIGH PERFORMANCE FACILITIES con 6 foto greyscale EFFETTO HOVER ombra e allarga-->
<!-- altra section con bg pugnazzi e frase Bruce Lee -->
<!-- sec MEET OUR TRAINER 3 schede con foto, testo e iconcine social, tasto per svelarne altri (js?); altro triangolino  EFFETTO HOVER ombra e allarga-->
<!-- PERFORMANCE NEWS schete foto e testo non affiancate; tasto READ ALL ARTICLES EFFETTO HOVER filtro rosso e compaiono icone link e zoom -->
<!-- sez Achieve Your Fitness Goals; titolo + p e tasto sfondo "parallasse" ?? -->
<!-- footer 3 menu + foto -->
<!-- bottom-bar stringa copyright + social + tasto per tornar su -->

<script>
import AvadaHeader from './components/AvadaHeader.vue'
import FooterAvada from './components/FooterAvada.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    AvadaHeader,
    FooterAvada
},
  data () {
    return {
    }

  }
}
</script>

<style lang="scss">

@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,200;0,400;0,700;1,200&display=swap');

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

#app {
  // font-family: Avenir, Helvetica, Arial, sans-serif;
  font-family: 'Montserrat', sans-serif;
  font-size: 0.75rem;
  background-color: $shark;
  color: white;
}

img {
    max-width: 100%;
}

.bg-basegrey {
  background-color: #25292b;
}

.bg-mediumgrey {
  background-color: #1f2123;
}

.bg-darkgrey {
  background-color: #1a1c1e;
}

.thick {
  font-weight: 700;
}

.half-thick {
  font-weight: 400;
  letter-spacing: 0.1rem;
}

input {
  width: 100%;
  background-color: #202325;
  border: 1px solid #2a2e30;
}

.small {
  font-size: small;
}

.large {
  font-size: large;
}

.txtgrey {
  color: #969596;
}

.icon {
  filter: invert(69%) sepia(26%) saturate(5726%) hue-rotate(318deg) brightness(90%) contrast(108%);
  padding: 6px;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  border: 1px solid  black;
}

.btn-form {
  background-color: #ee6059;
  color: #fafafa;
  width: 100%;
  text-align: center;
}

.bg-gym {
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  background-image: url('@/assets/img/gym_bkgd_bw-compressor.jpg');
}

.bg-banner {
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url('@/assets/img/home-parallax.jpg');
}

.bg-fists {
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  background-image: url('@/assets/img/home-testimonial-bg.jpg');
}

.social-square {
  display: inline-block;
  text-align: center;
  max-width: 25px;
  height: 25px;
  padding: 2px;
  margin-right: 4px;
  background-color: #1f2123;

  img {
    height: 8px;
    filter: invert(1);
  }

}

.btn-trasp {
  background-color: transparent;
  padding: 8px 24px;
  color: $edward;
  border: 1px solid $edward;
}

</style>

<!--   box-shadow: 0 -1px 10px rgba(0, 0, 0, .7); -->

<!--   .forefront-element {
    -webkit-transform: translateZ(999px) scale(.7);
    transform: translateZ(999px) scale(.7);
    z-index: 1;
  }

  .base-element {
    -webkit-transform: translateZ(0);
    transform: translateZ(0);
    z-index: 4;
  }

  .background-element {
    -webkit-transform: translateZ(-999px) scale(2);
    transform: translateZ(-999px) scale(2);
    z-index: 3;
  }
 -->
