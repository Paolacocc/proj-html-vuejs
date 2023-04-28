<script>
import { getImagePath } from '../utils/helpers';

export default {
    name: "AppPizzas",
    props: {
        image: String,
        title: String,
        price: String

    },
    methods: {
        getImagePath
    }

}
</script>

<template>
     <div class="pizza-carousel">
            <img :src="getImagePath(image)" alt="">
            <div class="pizza-text text-center p-4">
                <h5 class="title">{{ title }}</h5>
                <h5 class="price">{{ price }}</h5>
            </div>
        </div>
    </template>

<style scoped lang="scss">
@use "../style/partials/variables" as *;
.pizza-carousel {
  
    padding: 40px;
    width: calc(100 / 6 );
    flex-wrap: nowrap;
    img {
        max-width: none;
            width: 250px;
                 
        }
        .title {
            color: $text-light;
        }
        .price {
            color: $orange;
        }

}
</style>    