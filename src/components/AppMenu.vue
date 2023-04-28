<script>
import AppPizzas from './AppPizzas.vue';
import { getImagePath } from '../utils/helpers';



export default {
    name: "AppMenu",
    components: {
        AppPizzas
    },
    data() {
        return {
            pizzasArray: [
                {
                    pizzas: "h3-product-img-1a-100x100.png",
                    title: "BISMARK",
                    price: "$30.00"

                },
                {

                    pizzas: "h3-product-img-2a-150x150.png",
                    title: "BISMARK",
                    price: "$30.00"
                },
                {

                    pizzas: "h3-product-img-3a-150x150.png",
                    title: "FIORI DI ZUCCA",
                    price: "$7.00 - $50.00"
                },
                {

                    pizzas: "h3-product-img-4a-150x150.png",
                    title: "VALDOSTANA",
                    price: "$55.00"
                },
                {

                    pizzas: "h3-product-img-5a-150x150.png",
                    title: "PIZZA TARTUFATA",
                    price: "$45.00"
                },
                {

                    pizzas: "h3-product-img-6a-100x100.png",
                    title: "CAMPAGNOLA",
                    price: "$50.00 - $95.00"
                }
            ]
        }
    },

    methods: {
        getImagePath
    }
}


</script>

<template>
    <div class="menu-box">
        <div class="title text-center">
            <p class="top-title">CHOOSE YOUR FALAVOUR</p>
            <h3>THE BEST PIZZA MENU IN TOWN</h3>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quia autem excepturi, placeat expedita corrupti
                enim delectus quo rem minima at aut nesciunt inventore cum, </p>
        </div>
        <div class="choose-pizza d-flex">

            <AppPizzas v-for="(pizza, index) in pizzasArray" :key="index" :image="pizza.pizzas" :title="pizza.title"
            :price="pizza.price"/>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use "../style/partials/variables" as *;

.menu-box {
    height: 600px;
    margin-bottom: 60px;

    .title {
        width: 40%;
        margin: 60px auto;

        .top-title {
            color: $orange;
        }

        p {
            color: grey;
        }

    }

    .choose-pizza {
        width: 100%;
        overflow-x: scroll;

    }
}
</style>