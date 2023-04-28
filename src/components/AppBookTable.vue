<script>
export default {
    name: "AppBookTable"
}

</script>

<template>
    <div class="book-table d-flex justify-content-center align-content-center">
        <div class="input-info d-flex ">

            <input type="text" id="person" placeholder="1 Person">
            <h6>FOR</h6>
            <input type="text" id="date" placeholder="28/04/2023">
            <h6>AT</h6>
            <input type="text" id="time" placeholder="11:00">
            <button class="_ms-btn"><a href="">BOOK A TABLE</a></button>
            
        </div>
        
    </div>
    
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
.book-table {
    padding-top: 10px;
    height: 200px;
    max-width: 100%;
    background-image: url("../assets/img/h3-background-img-3.jpg");
    background-size: cover;

    .input-info {
        align-items: center;
        flex-wrap: wrap;
        h6 {
            color: white ;
            padding: 10px;
        }
        input,
        button {
            height: 40px;
            border-style: none;
            padding: 5px 20px;
        }
        ._ms-btn {
            margin-left: 40px;
            background-color: $orange;
            padding: 5px 40px;
        }
        
    }
}
</style>