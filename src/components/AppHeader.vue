<script>
import AppLinks from './AppLinks.vue';

export default {
    name: "AppHeader",
    components: {
        AppLinks
    },
    data() {
        return {
            HeaderLinks: [
                {
                    title: "HOME",
                    image: ""
                },
                {
                    title: "PAGES",
                    image: ""
                },
                {
                    title: "MENU",
                    image: ""
                },
                {
                    title: "",
                    image: "h5-logo-divided-header.png"
                },
                {
                    title: "EVENT",
                    image: ""
                },
                {
                    title: "BLOG",
                    image: ""
                },
                {
                    title: "LANDING",
                    image: ""
                }

            ]
        }
    }
}

</script>

<template>
    <div class="header">

        <div class="container">
            <div class="header-top" pt-4>
                <button class="btn">
                    <a href="">
                        ORDER ONLINE
                    </a>
                </button>
                <div class="main-links d-flex">
                    <AppLinks v-for="(link, index) in HeaderLinks" :key="index" :title="link.title" :image="link.image" />
                </div>
                <div class="action-icons">
                    <h6>
                        <img src="../assets/svg/svg-1.svg" alt="">
                        <a href="">CART</a>
                    </h6>
                    <h6>
                        <img src="../assets/svg/" alt="">
                        <a href="">SEARCH</a>
                    </h6>
                </div>
            </div>
            <div class="jumbotron">
                <img class="jumbo-img p-4" src="../assets/img/h3-rev-img-6.png" alt="">
            </div>
        </div>
    </div>
</template>



<style scoped lang="scss">
@use "../style/partials/variables" as *;



.header {
    background-color: $bkg-black;
    padding-bottom: 60px;

    .header-top {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-top: 30px;
        height: 150px;

        .btn {
            color: white;
            background-color: $orange;
            color: white;
           

            a {
                color: white;
            }
        }
        .main-links {
            height: 150px;
            flex-wrap: wrap;
            align-items: center;
            align-content: flex-start;
        }
        .action-icons {
            
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            img {}

            h6 {
                a {
                    padding-right: 20px;
                    color: white;

                }
                img {
                    padding-right: 5px;
                    filter: invert(100%);
                    vertical-align: bottom;
                }
            }
        }

       

    }
}


.jumbotron {
    background-image: url("../assets/img/h3-rev-img-5.png");
    background-repeat: no-repeat;
    background-size: contain;
    width: 70%;
    margin: 0 auto;
    display: flex;
    justify-content: center;

    .jumbo-img {
        width: 300px;
    }
}

a {
    text-decoration: none;
}
</style>
