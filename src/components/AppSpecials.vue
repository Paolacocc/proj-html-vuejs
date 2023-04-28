<script>
export default {
    name: "AppSpecial",
}
</script>

<template>
    <div class="specials">
        <img src="../assets/img/h1-img-4.jpg" alt="">

        <div class="special-menu">
            <h3>SPECIALS*</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus porro, </p>
            <ul>
                <li>
                    <div class="d-flex">
                        <h5 class="price">$10</h5>
                        <div class="description">
                            <h5>COMBO PICCOLO</h5>
                            <p>
                                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dicta quod
                            </p>
                        </div>
                    </div>

                </li>
                <li>
                    <div class="d-flex">
                        <h5 class="price">$20</h5>
                        <div class="description">
                            <h5>COMBO MEZZO</h5>
                            <p>
                                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dicta quod
                            </p>
                        </div>
                    </div>
                </li>
                <li>
                    <div class="d-flex">
                        <h5 class="price">$30</h5>
                        <div class="description">
                            <h5>COMBO GRANDE</h5>
                            <p>
                                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dicta quod
                            </p>
                        </div>
                    </div>
                </li>
            </ul>
            <div class="pizza-circle">
                <div class="pizza-slice">
                    <img class="pizza-sm" src="../assets/svg/svg-4.svg" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use "../style/partials/variables" as *;

@use "../style/general.scss" as *;

.specials {
    padding: 10px 0;
    display: flex;

    .special-menu {
        position: relative;
        padding: 60px 180px 60px 120px;
        .pizza-circle {
            position: absolute;
            top: 90%;
            left: 90%;
            transform: translate(-50%, -50%);
        }

       

            .price {
                margin-inline-end: 10px;
                color: $orange;
            }
        
    }

}

p {
    font-size: .8rem;
}

img {
    width: 50%;
}</style>