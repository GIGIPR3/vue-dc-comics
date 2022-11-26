<template>

    <div class="sfondo">

        <div class="contenitore m-auto d-flex justify-content-between">

            <div class="col bottoneCont d-flex align-items-center">
                <button> <b>SIGN-UP NOW!</b> </button>
            </div>


            <div class="social col">
                <div class="d-flex justify-content-end align-items-center h-100">

                    <span class="titoloB fs-5 me-3"> <b>FOLLOW US</b> </span>
                    
                    <img src="../assets/vue-dc-comics-1/img/footer-facebook.png" alt="">
                    <img src="../assets/vue-dc-comics-1/img/footer-twitter.png" alt="">
                    <img src="../assets/vue-dc-comics-1/img/footer-youtube.png" alt="">
                    <img src="../assets/vue-dc-comics-1/img/footer-pinterest.png" alt="">
                    <img src="../assets/vue-dc-comics-1/img/footer-periscope.png" alt="">

                    <!-- <div class="col d-inline-block">
                        <img src="../assets/vue-dc-comics-1/img/footer-facebook.png" alt="">
                    </div>
                    <div class="col">
                        <img src="../assets/vue-dc-comics-1/img/footer-twitter.png" alt="">
                    </div>
                    <div class="col">
                        <img src="../assets/vue-dc-comics-1/img/footer-youtube.png" alt="">
                    </div>
                    <div class="col">
                        <img src="../assets/vue-dc-comics-1/img/footer-pinterest.png" alt="">
                    </div>
                    <div class="col">
                        
                    </div> -->
                    
                </div>

            </div>




        </div>



    </div>

</template>

<script>

</script>


<style lang="scss" scoped>
.contenitore {
    width: 70%;
    height: 20%;
}

.sfondo {
    background-color: rgb(48, 48, 48);
    height: 80px;
    z-index: 2;
}

.bottoneCont{
    height: 80px;
}

button {
    color: white;
    background-color: rgb(48, 48, 48);
    border: 2px solid rgb(12, 124, 236);
    padding: 1.5% 2.5%;
/*     margin-top: 2.5%; */
}

img{
    margin-right: 2%;
}

.social {
    width: 30%;
    height: 80px;
/*     padding: 1.5%; */
}

.titoloB {
    color: rgb(12, 124, 236);
}
</style>