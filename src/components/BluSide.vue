<template>
    <div class="blue">
        <div class="container">

            <div class="flexRow">
                <img src="../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="" class="image">
                <div class="testo">
                    DIGITAL COMICS
                </div>
            </div>
            <div class="flexRow">
                <img src="../assets/vue-dc-comics-1/img/buy-comics-merchandise.png" alt="" class="image">
                <div class="testo">
                    DC MERCHANDISE
                </div>
            </div>
            <div class="flexRow">
                <img src="../assets/vue-dc-comics-1/img/buy-comics-subscriptions.png" alt="" class="image">
                <div class="testo">
                    SUBSCRIPTION
                </div>
            </div>
            <div class="flexRow">
                <img src="../assets/vue-dc-comics-1/img/buy-comics-shop-locator.png" alt="" class="image">
                <div class="testo">
                    COMIC SHOP LOCATOR
                </div>
            </div>
            <div class="flexRow">
                <img src="../assets/vue-dc-comics-1/img/buy-dc-power-visa.svg" alt="" class="images">
                <div class="testo">
                    DC POWER VISA
                </div>
            </div>



        </div>
    </div>
</template>


<script>

</script>


<style lang="scss" scoped>

.blue{
    background-color: rgb(12, 124, 236);
    font-size: small;
    color: white;
    padding: 3%;
    
}

.flexRow{
    display: flex;
    flex-direction: row;
}
.container{
    width: 65%;
    margin: auto;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
.image{
    height: 40px;
    margin-right: 10px;
}
.images{
    width: 40px;
    margin-right: 10px;
}

.testo{
    margin-top: 10%;
}



</style>