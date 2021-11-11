<template>
    <main id="site_main">
        <div class="content">
            <div class="container">
                <h2>&rarr; Content goes here &larr;</h2>
            </div>
        </div>
        <div class="menu_dc">
            <div class="container">
                <div class="icon">
                    <div class="img">
                        <img src="../assets/buy-comics-digital-comics.png" alt>
                    </div>
                    <h3>Digital comics</h3>
                </div>
                <div class="icon">
                    <div class="img">
                        <img src="../assets/buy-comics-merchandise.png" alt>
                    </div>
                    <h3>DC merchandise</h3>
                </div>
                <div class="icon">
                    <div class="img">
                        <img src="../assets/buy-comics-subscriptions.png" alt>
                    </div>
                    <h3>Subscription</h3>
                </div>
                <div class="icon">
                    <div class="img">
                        <img src="../assets/buy-comics-shop-locator.png" alt>
                    </div>
                    <h3>Comic shop locator</h3>
                </div>
                <div class="icon">
                    <div class="img">
                        <img style="height: 40px" src="../assets/buy-dc-power-visa.svg" alt>
                    </div>
                    <h3>DC power visa</h3>
                </div>
            </div>
        </div>
    </main>
</template>

<script>
export default {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#site_main {
    background-color: black;
    margin-top: 5px;
    .content {
        height: 150px;
        h2 {
            color: white;
            line-height: 150px;
        }
    }
    .menu_dc {
        background-color: #0282F9;
        color: white;
        display: flex;
        align-items: center;
        height: 150px;
        .container {
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            .icon {
                display: flex;
                justify-content: flex-start;
                align-items: center;
                img {
                    width: 100%;
                    height: 60px;
                }
                h3 {
                    text-transform: uppercase;
                    font-weight: 400;
                    font-size: 15px;
                    margin-left: 10px;
                }
            }
        }
    }
}
</style>