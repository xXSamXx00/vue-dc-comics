<template>
    <footer id="site_footer">
        <div class="container">
            <div class="link_footer">
                <div class="list">
                    <h3>Dc comics</h3>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">Tv</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>
                    <h3>Shop</h3>
                    <ul>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>
                </div>
                <div class="list">
                    <h3>DC</h3>
                    <ul>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy policy (New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>
                <div class="list">
                    <h3>Sites</h3>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>
            </div>
            <div class="logo_dc">
                <img src="../assets/dc-logo-bg.png" alt="">
            </div>
        </div>
    </footer>
</template>

<script>
export default {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#site_footer {
    background-image: url(../assets/footer-bg.jpg);
    background-size: cover;
    height: 400px;
    .container {
        display: flex;
        justify-content: space-between;
        .link_footer {
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            width: 40%;
            .list {
                ul {
                    list-style: none;
                }
                h3 {
                    color: white;
                }
                a {
                    color: #8f8f90;
                    text-decoration: none;
                }
            }
        }
        .logo_dc {
            object-fit: cover;
        }
    }
}
</style>