<template>
    <footer class="bg-mediumgrey container-fluid">
            <div class="row justify-content-center align-items-center py-4">
                <div class="col-7">
                    <div class="row justify-content-center align-items-center">
                        <div class="col-3 p-2">
                            <ul class="nav flex-column">
                               <li class="nav-item">
                                    <a class="nav-link active" aria-current="page" href="#">Active</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Link</a>
                                </li>
                                 <li class="nav-item">
                                    <a class="nav-link" href="#">Link</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link disabled">Disabled</a>
                                </li>
                            </ul>
                        </div>
                        <div class="col-3 p-2">
                            <ul class="nav flex-column">
                               <li class="nav-item">
                                    <a class="nav-link active" aria-current="page" href="#">Active</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Link</a>
                                </li>
                                 <li class="nav-item">
                                    <a class="nav-link" href="#">Link</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link disabled">Disabled</a>
                                </li>
                            </ul>
                        </div>    
                        <div class="col-3 p-2">                            
                            <ul class="nav flex-column">
                               <li class="nav-item">
                                    <a class="nav-link active" aria-current="page" href="#">Active</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Link</a>
                                </li>
                                 <li class="nav-item">
                                    <a class="nav-link" href="#">Link</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link disabled">Disabled</a>
                                </li>
                            </ul>
                        </div>
                        <div class="col-3 p-2 text-center">                            
                            <img :src="require('../assets/img/gym_ad-compressor.jpg')" alt="">
                        </div>
                    </div>
                </div>
            </div>
        <div class="bg-darkgrey row justify-content-center align-items-center">
            <div class="col-7">
                <div class="row justify-content-between align-items-center py-4">
                    <span class=" col-9 little txt-grey">
                        Copyright 2012-2020 | AvadaGym Theme by Evil Master One | All Rights Reserved | Powered by The choosen One
                    </span>
                    <div class="col-3">
                        <div class="row no-wrap justify-content-end">
                            <div class="social-square">
                                <img :src="require('../assets/img/soc-facebook.svg')" alt="">
                            </div>
                            <div class="social-square">
                                <img :src="require('../assets/img/soc-twitter.svg')" alt="">
                            </div>
                            <div class="social-square">
                                <img :src="require('../assets/img/soc-instagram.svg')" alt="">
                            </div>  
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
  name: 'FooterAvada'  
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


li.nav-item {
    font-size: 0.40rem;
}

.little {
        font-size: 0.35rem;

}
a.nav-link {
    color: #aeafae;
}

.social-square {
    display: inline-block;
    text-align: center;
    max-width: 25px;
    min-width: 25px;
    height: 25px;
    padding: 2px;
    margin-right: 4px;
    background-color: #d3615e;
}

</style>
