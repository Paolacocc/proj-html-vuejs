<script>
export default {
    name: 'AppFooter'
}
</script>

<template>
    <div class="footer d-flex">
        <div class="footer-info ">
            <div class="footer-row d-flex">
                
                <div class="find ">
                    <ul>
                        <li class="find-title text-uppercase">
                            <h5>
                                find our restaurants
                            </h5>
                        </li>
                        <li>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
                            </p>
    
                        </li>
                        <li>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur 
                            </p>
    
                        </li>
                        <li>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipisicing 
                            </p>
    
                        </li>
                        <li>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur 
                            </p>
    
                        </li>
                        
    
                    </ul>
                </div>
                <div class="hours">
                    <ul>
                        <li class="find-title text-uppercase">
                            <h5>WORKING HOURS</h5>
                        </li>
                        <li>
                            <h6>MONDAY</h6>
                            <p class="red">kitchen closed</p>
                        </li>
                        <li>
                            <h6 class="text-uppercase">tuesday until friday</h6>
                            <p>9:00 - 22:00</p>
                        </li>
                        <li>
                            <h6 class="text-uppercase">saturday <span class="red">*</span></h6>
                            <p>Saturday 11am to midnight</p>
                        </li>
                        <li>
                            <h6 class="text-uppercase">sunday</h6>
                            <p>9:00 - 22:00</p>
                        </li>
                        <li>
                            <div class="follow-us d-flex">

                                <h6 class="text-uppercase">follow us:</h6>
                                <a href=""><i class="fa-brands fa-twitter"></i></a>
                                <a href=""><i class="fa-brands fa-facebook-f"></i></a>
                                <a href=""><i class="fa-brands fa-square-instagram"></i></a>
                                <a href=""><i class="fa-brands fa-linkedin-in"></i></a>
                            </div>
                        </li>
                    </ul>
                </div>
                <div class="phrase">
                    <h4>THE DON PEPPE CREW FIRST AND FOREMOST VALUES AN AUTENTIC, WELL BAKED SLICE OF PIZZA</h4>
                </div>
            </div>
        </div>
        <div class="footer-img">
            <img src="../assets/img/footer-img-1.jpg" alt="">
        </div>

    </div>
    <img src="../assets/img" alt="">
</template>

<style scoped lang="scss">
@use "../style/partials/variables" as *;

.footer {
    color: $lightgray;
    height: 100%;


    .footer-info {
        background-color: $bkg-black;
        width: 50%;
        .footer-row {
            padding: 10px;
            i {
                color: white;
                margin-left: 5px;
                padding: 3px;
                font-size: .8rem;
            }
.red {
    color: $orange;
}
            .find {
                width: 30%;
            }
            h5,
            h6 {
                color: $text-light;
            }
            ul,
            h4 {
                padding: 40px;
            }
            .phrase {
                width: 30%;
            }
            
        }
    }
  p {
    font-weight: 100;
  }

    .footer-img {
        width: 50%;
        img {
            max-width: 100%;
            height: auto;
        }

    }
}
</style>