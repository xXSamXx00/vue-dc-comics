<template>
    <footer id="site_footer">
        <div class="link_footer">
            <div class="container">
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
        </div>
        <div class="contact">
            <div class="container">
                <div class="button">
                    <button>Sign-up now&excl;</button>
                </div>
                <div class="socials">
                    <h3>Follow Us</h3>
                    <div class="social">
                        <img src="../assets/footer-facebook.png" alt="">
                    </div>
                    <div class="social">
                        <img src="../assets/footer-twitter.png" alt="">
                    </div>
                    <div class="social">
                        <img src="../assets/footer-youtube.png" alt="">
                    </div>
                    <div class="social">
                        <img src="../assets/footer-pinterest.png" alt="">
                    </div>
                    <div class="social">
                        <img src="../assets/footer-periscope.png" alt="">
                    </div>
                </div>
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
    .link_footer {
        background: url(../assets/dc-logo-bg.png) 80% no-repeat, url(../assets/footer-bg.jpg) no-repeat;
        background-size: 610px, cover;
        height: 400px;
        display: flex;
        .container {
            display: flex;
            .list {
                margin-right: 30px;
                ul {
                    list-style: none;
                }
                h3 {
                    color: white;
                    text-transform: uppercase;
                    margin: 30px 0 15px;
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
    .contact {
        background-color: #303030;
        height: 100px;
        .container {
            display: flex;
            justify-content: space-between;
            height: 100%;
            align-items: center;
            .button button {
                text-transform: uppercase;
                font-size: 1rem;
                padding: 12px;
                color: white;
                background-color: #303030;
                border: 2px solid #0282F9;
                cursor: pointer;
            }
            .socials {
                display: flex;
                align-items: center;
                .social {
                    margin-left: 20px;
                    img {
                        cursor: pointer;
                    }
                }
                h3 {
                    color: #0282F9;
                    text-transform: uppercase;
                    margin-right: 10px;
                }
            }
        }
    }
}
</style>