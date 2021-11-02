<template>
<div class="home">
    <div class="container">
        <div class="row">
            <div class="col-sm-12 col-md-6">
                <div class="img">
                    <img src="@/assets/image/TechPay.svg" alt="svg">
                </div>
                <div class="info">
                    <h2>Is Your Best Choise For What You Want</h2>
                    <p>TechPay is an online store that contains all your needs of mobiles, laptops, and headphones, with excellent quality and reasonable price.</p>
                    <a href="#products" class="link btn btn-blue">Explore</a>
                </div>
            </div>
            <div class="col-sm-12 col-md-6 slider">
                <div id="carouselExampleSlidesOnly" class="carousel slide carousel-fade" data-bs-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="@/assets/image/header/8.jpg" class="d-block w-100 rounded-3" alt="image2">
                        </div>
                        <div class="carousel-item">
                            <img src="@/assets/image/header/2.jpg" class="d-block w-100 rounded-3" alt="image4">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: "home",
}
</script>

<style lang="scss" scoped>
@import "../scss/style.scss";

/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    .home {
        .container {
            margin-top: 150px;  
            line-height: 2 !important;
            .slider{
                margin-top: 40px !important;
            }
            .row {
                >div {
                    width: 95%;
                    margin: auto;
                }

                .img {
                    width: 70% !important;
                }

                h2 {
                    font-weight: bold;
                    margin-bottom: 20px;
                
                }
                p{
                    margin-bottom: 25px;
                }
                .info {
                    a {
                        text-align: center;
                        margin: 15px auto !important;
                        margin-right: auto !important;
                        // width: 100px;
                        display: inline !important;
                    }
                }
            }

        }
    }
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
    .info {
        line-height: 1.2 !important;
        margin-top: 14px !important;

        p {
            font-size: 20px !important;
        }

        h2 {
            font-size: 20px !important;
            font-weight: bold;
        }
    }

    .img {
        width: 55% !important;
    }

    .info {
        button {
            text-align: center;
            display: inline !important;
            margin: 15px 0px;
        }
    }
}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
    .info {
        margin-top: 20px !important;
        a {
                text-align: center !important;
                margin: auto !important;
                width: 100px !important;
                display: block !important;
            }
        p {
            font-size: 20px;
            line-height: 1.5 !important;
        }

        h2 {
            font-size: 30px !important;
            margin-bottom: 10px;
        }
    }

    .img {
        width: 80% !important;
    }
     
}

.home {
    .container {
        margin-top: 150px;

        .img {
            width: 80%;

            img {
                width: 100%;
            }
        }

        .info {
            margin-top: 30px;
            text-align: left;

            p {
                font-size: 20px;
                // margin-bottom: 10px;
            }

            a {
                text-align: center;
                margin: auto;
                width: 100px;
                display: block;
            }
        }
    }
}
</style>
