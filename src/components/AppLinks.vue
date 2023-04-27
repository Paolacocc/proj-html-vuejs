<script>
import { getImagePath } from '../utils/helpers';
export default {
    name: "AppLinks",
    props: {
        title: String,
        image: String,
    },
    methods: {
        getImagePath
    }

}

</script>

<template>
    
        <div class="header-links">
            <img :src="getImagePath(image)" alt="">
            <h6 class="title">
                <a class="text-decoration-none" href="">{{ title }}</a>
            </h6>
        </div>

</template>

<style scoped lang="scss">
.header-links {
    padding: 10px;
    color: white;
    a {
        color: white;
    }
}
img {
    width: 150px;
  
}
</style>
