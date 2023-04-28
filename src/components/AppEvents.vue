<script>
import { getImagePath } from "../utils/helpers"
export default {
    name: "AppEvents",
    // props: {
    //     eventImg :{
    //         image: String
    //     }
    // },
    // methods: {
    //     getImagePath
    // }
}
</script>

<template>
    <div class="img-events d-flex">
        <img src="../assets/img/h3-img-1.jpg" alt="">
        <img src="../assets/img/h3-img-2.jpg" alt="">
        <img src="../assets/img/h3-img-3.jpg" alt="">
        <img src="../assets/img/h3-img-4.jpg" alt="">
    </div>

    <div class="quotes">
        <div class="quotes-text">
            <h3>"FORGET THE TRENDY PIZZA SHOPS. THIS HIDDEN SPOT MAKES THE BEST NEW<br>
                YORK-STYIE PIZZA SIGIN NAPIES"</h3>
            <h6>washington post 2018</h6>
        </div>
        <div class="pizza-circle">
            <div class="pizza-slice">
                <img class="pizza-sm" src="../assets/svg/svg-4.svg" alt="">
            </div>
        </div>
    </div>

    <!-- <img :src="getImagePath(image)" alt=""> -->
</template>

<style scoped lang="scss">
@use "../style/partials/variables" as *;
@use "../style/general.scss" as *;


.img-events {

    img {
        padding: 10px 5px;
        width: calc(100% / 4);
    }

}

.quotes {
    position: relative;
    background-image: url(../assets/img/h3-testimonials-bckgrnd.jpg);
    width: 100%;
    background-position: center;
    height: 400px;

    .pizza-circle {
        position: absolute;
        top: 90%;
        left: 90%;
        transform: translate(-50%, -50%);
    }

    .quotes-text {

        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);

        h3 {
            text-align: center;
        }

        h6 {
            color: $orange;
            text-transform: uppercase;
            text-align: center;
        }

    }



}
</style>