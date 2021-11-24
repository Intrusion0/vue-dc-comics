<template>
    <footer>
        <section id="comics-footer">
            <div class="ms-container">
                <div class="nav-footer">
                    <div>
                        <h3>DC COMICS</h3>
                        <ul>
                            <li>
                                <a href="#">
                                    Characters
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Comics
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Movies
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    TV
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Games
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Videos
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    News
                                </a>
                            </li>
                        </ul>
                        <h3>SHOP</h3>
                        <ul>
                            <li>
                                <a href="#">
                                    Shop DC
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Shop DC Collectibles
                                </a>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h3>DC</h3>
                        <ul>
                            <li>
                                <a href="#">
                                    Terms Of Use
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Privacy policy (New)
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Ad Choices
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Advertising
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Jobs
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Subscriptions
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Talent Workshops
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    CPSC Certificates
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Ratings
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Shop Help
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Contact Us
                                </a>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h3>SITES</h3>
                        <ul>
                            <li>
                                <a href="#">
                                    DC
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    MAD Magazine
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    DC Kids
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    Dc Universe
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    DC Power Visa
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="logo-footer">
                    <img src="../assets/img/dc-logo-bg.png" alt="logo dc">
                </div>
            </div>
        </section>
        <section id="social-footer">
            <div class="ms-container">
                <div class="btn-signup">
                    <a href="#">SIGN-UP NOW!</a>
                </div>
                <div class="socials">
                    <span>
                        FOLLOW US
                    </span>
                    <ul>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-facebook.png" alt="logo facebook">
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-twitter.png" alt="logo twitter">
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-youtube.png" alt="logo youtube">
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-pinterest.png" alt="logo pinterest">
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-periscope.png" alt="logo periscope">
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </section>
    </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
footer {
    display: flex;
    flex-direction: column;
    // debug
    height: 450px;

    #comics-footer {
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        overflow: hidden;

        .nav-footer {
            display: flex;
            width: 50%;
            padding: 20px 0;

            & div {
                margin-right: 30px;
            }

            h3 {
                color: white;
                margin: 20px 0 20px;
                font-size: 18px;
            }

            ul {
                list-style: none;

                li {
                    margin: 5px 0;

                    & a {
                        text-decoration: none;
                        color: #959595;
                        font-size: 14px;
                    }
                }
            }
        }

        .logo-footer {
            display: flex;
            justify-content: flex-end;
            width: 50%;
            position: relative;
            top: -100px;
            left: 0;
        }
    }

    #social-footer {
        width: 100%;
        background-color: #303030;
        padding: 20px 0;

        .btn-signup {
            display: flex;
            align-items: center;
            width: 50%;

            a {
                text-decoration: none;
                color: #fff;
                border: 2px solid #1068ba;
                padding: 10px 13px;
            }
        }

        .socials {
            display: flex;
            justify-content: flex-end;
            align-items: center;
            width: 50%;

            span {
                color: #0282f9;
                font-weight: 600;
                margin-right: 20px;
            }

            ul {
                list-style: none;

                & li {
                    display: inline-block;
                    margin: 0 10px;
                }
            }
        }
    }
}
</style>
