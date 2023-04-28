<script>
export default {
    name:"AppAssociates"
}
</script>


<template>
    <div class="associates">
        <img src="../assets/img/h1-clients-img-4.png" alt="">
        <img src="../assets/img/h1-clients-img-3.png" alt="">
        <img src="../assets/img/h1-clients-img-1.png" alt="">
        <img src="../assets/img/h1-clients-img-2.png" alt="">
        <img src="../assets/img/h1-clients-img-5.png" alt="">


    </div>
</template>

<style scoped lang="scss">
@use "../style/partials/variables" as *;

.associates {
    height: 200px;
    background-color: $lightgray;
    text-align: center;
    line-height: 200px;
    img {
        width: 150px;
    }
}
</style>