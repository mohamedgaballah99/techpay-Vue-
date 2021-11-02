<template>
<div class="cart">
    <div class="container">
        <h1 class="text-center">My Favourite</h1>
        <div class="row rounded-3">
            <div class="col">
                <img src="@/assets/image/products/6.jpg" width="50%" class="rounded-3">
            </div>
            <div class="info col">
                <h4>Iphone</h4>
                <h4>40$</h4>
                <p>some quick example text to build on the card title and make up the bulk of the card's contant</p>
            </div>
            <div class="col">
                <button class="btn btn-danger">Delete</button>
            </div>
        </div>
        <div class="row rounded-3">
            <div class="col">
                <img src="@/assets/image/products/11.jpg" width="50%" class="rounded-3" height="120px">
            </div>
            <div class="info col">
                <h4>Laptop</h4>
                <h4>90$</h4>
                <p>some quick example text to build on the card title and make up the bulk of the card's contant</p>
            </div>
            <div class="col">
                <button class="btn btn-danger">Delete</button>
            </div>
        </div>
        <div class="row rounded-3" style="margin-bottom:40px">
            <div class="col">
                <img src="@/assets/image/products/4.jpg" width="50%" class="rounded-3" height="120px">
            </div>
            <div class="info col">
                <h4>HeadPhone</h4>
                <h4>10$</h4>
                <p>some quick example text to build on the card title and make up the bulk of the card's contant</p>
            </div>
            <div class="col">
                <button class="btn btn-danger">Delete</button>
            </div>
        </div>
        

    </div>
</div>
</template>

<script>
export default {
    name: "Fav",
}
</script>

<style lang="scss" scoped>
@import"../scss/style.scss";

/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    .row {
        width: 95% !important;
        margin: 20px auto !important;

        img {
            width: 60px;
            height: 60px;
        }

        p {
            font-size: 11px !important;
            width: 100% !important;
            line-height: 1.5 !important;
        }
    }
}

.cart {
    margin-top: 100px;

    .container {
        h1 {
            color: $primary-color;
            margin-bottom: 30px;
        }

        .row {
            box-shadow: 0px 0px 10px 2px rgba(128, 128, 128, 0.712);
            padding: 20px 0px 10px 0px;
            display: flex;
            align-items: center;
            margin-top: 40px;
 img {
            width: 110px;
            height:110px;
        }
            .col {
                h4 {
                    margin-bottom: 10px;
                    font-weight: bold;
                }

                h4:last-of-type {
                    font-weight: bold;
                    color: $primary-color;
                    font-size: 20px;
                }

                .btn-danger {
                    padding: 5px 7px !important;
                }
            }
        }
    }
}
</style>
