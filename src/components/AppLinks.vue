<script>
export default {
    name: "AppLinks",
    props: {
        title: String,
        image: String,
    }

}

</script>

<template>
    <div class="header-links" v-if="title === ''">
        <img :src="image" alt="">
    </div>
    <div class="header-links" v-else-if="image === ''">
        <h6 class="title">{{ title }}</h6>
    </div>
    <div class="header-links" v-else>
        <img :src="image" alt="">
        <h6 class="title">{{ title }}</h6>
    </div>
</template>

<style scoped></style>
