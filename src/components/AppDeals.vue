<script>
export default {
    name: "AppDeals"
}
</script>

<template>
    <div class="deals-section d-flex">
        <div class="deals">
            <div class="deals-info">

                <p>MADE WITH LOVE</p>
                <h3>DELISH PIZZA DEALS</h3>
                <ul>
                    <li>
                        <div class="deal-list d-flex align-items-center ">

                            <div class="date">
                                <h2 class="fw-bold fs-1">02</h2>
                                <h4 class="text-uppercase">nov</h4>
                            </div>
                            <div class="place p-4">
                                <h4>TRADITIONAL NAPOLITAN PIE IN KYOTO PIZZA MERCATO</h4>
                                <p><i class="fa-solid fa-location-dot p-1"></i>204 E. Pizzetta Tommaso</p>
                            </div>

                        </div>

                    </li>
                    <li>
                        <div class="deal-list d-flex align-items-center ">

                            <div class="date">
                                <h2 class="fw-bold fs-1">02</h2>
                                <h4 class="text-uppercase">nov</h4>
                            </div>
                            <div class="place p-4">
                                <h4>TRADITIONAL NAPOLITAN PIE IN KYOTO PIZZA MERCATO</h4>
                                <p><i class="fa-solid fa-location-dot p-1"></i>204 E. Pizzetta Tommaso</p>
                            </div>

                        </div>
                    </li>
                    <li>
                        <div class="deal-list d-flex align-items-center ">

                            <div class="date">
                                <h2 class="fw-bold fs-1">02</h2>
                                <h4 class="text-uppercase">nov</h4>
                            </div>
                            <div class="place p-4">
                                <h4>TRADITIONAL NAPOLITAN PIE IN KYOTO PIZZA MERCATO</h4>
                                <p><i class="fa-solid fa-location-dot p-1"></i>204 E. Pizzetta Tommaso</p>
                            </div>

                        </div>
                    </li>

                </ul>
            </div>
        </div>
        <div class="deals-img">
            <img src="../assets/img/h3-img-5a.jpg" alt="">
        </div>

    </div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

.deals-section {
    padding: 10px 0 10px;
    .deals {
        
        width: 50%;
        background-color: $bkg-black;
        color: white;

        .deals-info {
            padding: 100px;
            .deal-list {
                width: 80%;

                border-bottom: 1px dotted $text-light;
            }

            .date {
                box-sizing: content-box;
            }

            p,
            h2 {
                color: $orange;
            }
        }
    }

    .deals-img {
        width: 50%;
        
        img {
            max-width: 100%;
            height: auto;
        }
    }

}</style>