<template>

    <div class="sfondo">

        <div>

            <div class="linkSection">
                <div class="flex">

                    <div class="colonna1">

                        <div class="titoloW">
                            <h3>DC COMICS</h3>
                        </div>

                        <div>

                            <ul>
                                <li>Characters</li>
                                <li>Comics</li>
                                <li>Movies</li>
                                <li>TV</li>
                                <li>Games</li>
                                <li>Videos</li>
                                <li>News</li>
                            </ul>
                          
                        </div>

                        <div class="titoloW titolo2">
                            <h3>SHOP</h3>
                        </div>

                        <div>
                            <ul>
                                <li>Shop DC</li>
                                <li>Shop DC Collectibles</li>
                            </ul>
                        </div>





                    </div>

                    <div class="colonna">

                        <div class="titoloW">
                            <h3>DC</h3>
                        </div>
                
                        <div>

                            <ul>
                                <li>Term Of Use</li>
                                <li>Privacy policy (New)</li>
                                <li>Ad Choices</li>
                                <li>Advertising</li>
                                <li>Jobs</li>
                                <li>Subscription</li>
                                <li>Talent Workshops</li>
                                <li>CPSC Certificates</li>
                                <li>Rating</li>
                                <li>Shop Help</li>
                                <li>Contact Us</li>

                            </ul>

                        </div>


                    </div>

                    <div class="colonna">

                        <div class="titoloW">
                            <h3>SITES</h3>
                        </div>

                        <div>

                            <ul>
                                <li>DC</li>
                                <li>MAD Magazine</li>
                                <li>DC Kids</li>
                                <li>DC Universe</li>
                                <li>DC Power Visa</li>

                            </ul>

                        </div>


                    </div>


                </div>

            </div>














        </div>








    </div>

</template>


<script>


</script>



<style lang="scss" scoped>
.sfondo {
    background-image: url(../assets/vue-dc-comics-1/img/footer-bg.jpg);

}

.linkSection {
    width: 70%;
    margin: auto;
    padding-bottom: 5%;
    padding-top: 1%;
    display: flex;
}

.flex {
    display: flex;
}

.titoloW {
    color: white;
    /*     padding-top: 15%; */
}

.titolo2 {
    padding-top: 20%;
}

.colonna {
    margin-left: 15%;
    padding-top: 15%;
}

.colonna1 {
    padding-top: 15%;
    padding-left: 5%;
}
    
    
    
    
li:hover{
    color:rgb(201, 201, 201);
    cursor: pointer;
}

ul {
    list-style-type: none;
    padding-left: 0;
    margin-top: 1%;
    color: gray;
    white-space: nowrap;

    li {
        padding-top: 7px;
        font-size: small;
        white-space: nowrap;
    }


}
</style>