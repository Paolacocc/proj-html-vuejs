<script>
export default {
    name: "AppSpecial",
}
</script>

<template>
    <div class="specials">
        <img src="../assets/img/h1-img-4.jpg" alt="">

        <div class="special-menu">
            <h2>SPECIALS*</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus porro, </p>
            <ul>
                <li>
                    <div class="d-flex">
                        <h4 class="price">$10</h4>
                        <div class="description">
                            <h4>COMBO PICCOLO</h4>
                            <p>
                                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dicta quod corrupti maxime
                                molestias magni ipsum,
                            </p>
                        </div>
                    </div>

                </li>
                <li>
                    <div class="d-flex">
                        <h4 class="price">$20</h4>
                        <div class="description">
                            <h4>COMBO MEZZO</h4>
                            <p>
                                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dicta quod corrupti maxime
                                molestias magni ipsum,
                            </p>
                        </div>
                    </div>
                </li>
                <li>
                    <div class="d-flex">
                        <h4 class="price">$30</h4>
                        <div class="description">
                            <h4>COMBO GRANDE</h4>
                            <p>
                                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dicta quod corrupti maxime
                                molestias magni ipsum,
                            </p>
                        </div>
                    </div>
                </li>
            </ul>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use "../style/partials/variables" as *;
.specials {
    padding: 10px 0;
    display: flex;

    .special-menu {
        padding: 60px;
        ul {
            list-style: none;
            margin: 0;
            padding: 0;
            .price {
                margin-inline-end: 10px;
                color: $orange;
            }
        }
    }

}

img {
    width: 50%;
}
</style>