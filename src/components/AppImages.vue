<script>
export default {
    name: "AppImages"
}
</script>

<template>
    <div class="top-img">
        <h2 class="_ms-text text-center">GO AHEAD AND
            BUILD YOUR
            OWN PIZZA
            WE WON'T
            JUDGE!</h2>
        <div class="pizza-circle">
            <div class="pizza-slice">
                <img class="pizza-sm" src="../assets/svg/svg-4.svg" alt="">
            </div>
        </div>
    </div>
    <div class="bottom-img">
        <div class="team-img d-flex">
            <img src="../assets/img/h1-team-1a-700x700.jpg" alt="">
            <img src="../assets/img/h1-team-2a.jpg" alt="">
            <img src="../assets/img/h1-team-3a.jpg" alt="">
            <img src="../assets/img/h1-team-4a.jpg" alt="">

        </div>

        <div class="pizza-circle">
            <div class="pizza-slice">
                <img class="pizza-sm" src="../assets/svg/svg-4.svg" alt="">
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.top-img {
    position: relative;
    height: 400px;
    background: url("../assets/img/h3-background-img.jpg");
    background-size: 80%;
    background-repeat: repeat;
    background-position-x: 60%;
    background-position-y: 60%;
._ms-text {
    color: white;
    line-height: 400px;
}
    .pizza-circle {
        position: absolute;
        top: 90%;
        left: 90%;
        transform: translate(-50%, -50%);
    }

}

.bottom-img {
    
    position: relative;
    padding-top: 10px;
    width: calc(100% / 4);
    object-fit: cover;
    img {
        max-width: 100%;
            height: auto;
    }
    .pizza-circle {
        position: absolute;
        top: 90%;
        left: 100%;
        transform: translate(-50%, -50%);
    }
}

</style>