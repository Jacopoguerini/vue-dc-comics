<template>

  <footer>
    <div class="container">
        <!-- footer top -->
        <section class="footer-top">
            <!-- first column -->
            <div>
                <!-- DC Comics -->
                <h2>dc comics</h2>
                <ul>
                    <li>
                        <a href="#">Characters</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Movies</a>
                    </li>
                    <li>
                        <a href="#">TV</a>
                    </li>
                    <li>
                        <a href="#">Games</a>
                    </li>
                    <li>
                        <a href="#">Videos</a>
                    </li>
                    <li>
                        <a href="#">News</a>
                    </li>
                </ul>
                <!-- /DC Comics -->
                <!-- shop -->
                <h2>dc shop</h2>
                <ul>
                    <li>
                        <a href="#">Shop DC</a>
                    </li>
                    <li>
                        <a href="#">Shop DC Collectibles</a>
                    </li>
                </ul>
                <!-- /shop -->
            </div>
            <!-- /first column -->

            <!-- second column -->
            <div>
                <!-- DC -->
                <h2>dc</h2>
                <ul>
                    <li>
                        <a href="#">Terms of Use</a>
                    </li>
                    <li>
                        <a href="#">Privacy Policy (New)</a>
                    </li>
                    <li>
                        <a href="#">Advertising</a>
                    </li>
                    <li>
                        <a href="#">Jobs</a>
                    </li>
                    <li>
                        <a href="#">Subsriptions</a>
                    </li>
                    <li>
                        <a href="#">CPSC Certificates</a>
                    </li>
                    <li>
                        <a href="#">Ratings</a>
                    </li>
                    <li>
                        <a href="#">Shop Help</a>
                    </li>
                    <li>
                        <a href="#">Contact Us</a>
                    </li>                    
                </ul>
                <!-- /DC Comics -->
            </div>
            <!-- /second column -->

            <!-- third column -->
            <div>
                <!-- Sites -->
                <h2>sites</h2>
                <ul>
                    <li>
                        <a href="#">DC</a>
                    </li>
                    <li>
                        <a href="#">MAD Magazine</a>
                    </li>
                    <li>
                        <a href="#">DC Kids</a>
                    </li>
                    <li>
                        <a href="#">DC UNIVERSE INFINITE</a>
                    </li>
                    <li>
                        <a href="#">DC Power Visa</a>
                    </li>                 
                </ul>
                <!-- /sites -->
            </div>
            <!-- /third column -->
        </section>
        <!-- /footer top -->
    </div>

    <!-- footer bottom -->
    <section class="footer-bottom">
        <div class="container">
            <span>sign-up now&excl;</span>
        </div>
    </section>
    <!-- /footer bottom -->


  </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    @import '../style/variables.scss';
    
    footer {
        clear: both;
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
    }

    .container {
        background-image: url('../assets/img/dc-logo-bg.png');
        background-position: center right;
        background-repeat: no-repeat;
    }
    
    .footer-top {
        padding: 40px 0;
        display: flex;

        div {
            margin-right: 35px;
        }
    }

    .footer-bottom {
        height: 100px;
        background-color: #303030;
    }

    h2 {
        color: white;
        font-size: 22px;
        text-transform: uppercase;
        margin-top: 10px;
    }

    a {
        color: #959595;
        font-size: 12px;

        &:hover {
            color: $brandBlue;
        }
    }

    ul {
        margin-top: 5px;
    }
</style>