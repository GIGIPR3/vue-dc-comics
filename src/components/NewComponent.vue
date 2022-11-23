<template>
    <div class="header">
        <div>
            <img src="../assets/vue-dc-comics-1/img/dc-logo.png" alt="logo" class="logo">
        </div>
        <div class="menu">
            <div>CHARACTERS</div>
            <div class="selected">COMICS</div>
            <div>MOVIES</div>
            <div>TV</div>
            <div>GAMES</div>
            <div>COLLECTIBLES</div>
            <div>VIDEOS</div>
            <div>FANS</div>
            <div>NEWS</div>
            <div>SHOP</div>
        </div>
    </div>
</template>

<script>

</script>

<!-- <style scoped lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style> -->
<style lang="scss" scoped>

.header{
    display: flex;
    flex-direction: row;
    width: 65%;
    
    margin: auto;
    justify-content: space-between;
    background-color: gray;
}

.logo{
    width: 70px;
}

.menu{
    display: flex;
    flex-direction: row;
    font-size: small;
    justify-content: space-around;
    width: 70%;
    padding-top: 2%;
}

.selected{
    
}

</style>