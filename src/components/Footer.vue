<template>
    <footer>
        <section id="comics-footer">
            <div class="ms-container">
                <div class="nav-footer">
                    <div>
                        <h3>DC COMICS</h3>
                        <ul>
                            <li>
                                Characters
                            </li>
                            <li>
                                Comics
                            </li>
                            <li>
                                Movies
                            </li>
                            <li>
                                TV
                            </li>
                            <li>
                                Games
                            </li>
                            <li>
                                Videos
                            </li>
                            <li>
                                News
                            </li>
                        </ul>
                        <h3>SHOP</h3>
                        <ul>
                            <li>
                                Shop DC
                            </li>
                            <li>
                                Shop DC Collectibles
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h3>DC</h3>
                        <ul>
                            <li>
                                Terms Of Use
                            </li>
                            <li>
                                Privacy policy (New)
                            </li>
                            <li>
                                Ad Choices
                            </li>
                            <li>
                                Advertising
                            </li>
                            <li>
                                Jobs
                            </li>
                            <li>
                                Subscriptions
                            </li>
                            <li>
                                Talent Workshops
                            </li>
                            <li>
                                CPSC Certificates
                            </li>
                            <li>
                                Ratings
                            </li>
                            <li>
                                Shop Help
                            </li>
                            <li>
                                Contact Us
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h3>SITES</h3>
                        <ul>
                            <li>
                                DC
                            </li>
                            <li>
                                MAD Magazine
                            </li>
                            <li>
                                DC Kids
                            </li>
                            <li>
                                Dc Universe
                            </li>
                            <li>
                                DC Power Visa
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
        display: flex;
        width: 100%;
        background-image: url('../assets/img/footer-bg.jpg');
        // debug
        height: 400px;

        .nav-footer {
            display: flex;
        }
    }

    #social-footer {
        width: 100%;
        background-color: #303030;
        // debug
        height: 100px;
    }
}
</style>
