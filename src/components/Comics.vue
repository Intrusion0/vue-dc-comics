<template>
    <div class="comics">
        <section id="content-main">
            <div class="ms-container">
                <span>
                    --&#62; Content goes here &#60;--
                </span>
            </div>
        </section>
        <section id="icons-main">
            <div class="ms-container">
                <nav>
                    <ul>
                        <li v-for="comicsEl, j in comicsElements" :key="j">
                            <a :href="comicsEl.link">
                                <img :src="comicsEl.picture" :alt="comicsEl.text">
                                <span>DIGITAL COMICS</span>
                            </a>
                        </li>
                    </ul>
                </nav>
            </div>
        </section>
    </div>
</template>

<script>
export default {
  name: 'Comics',
  data() {
      return {
          comicsElements: [
            {
                text: 'DIGITAL COMICS',
                link: '#',
                picture: require('@/assets/img/buy-comics-digital-comics.png')
            },
            {
                text: 'DC MERCHANDISE',
                link: '#',
                picture: require('@/assets/img/buy-comics-merchandise.png')
            },
            {
                text: 'SUBSCRIPTION',
                link: '#',
                picture: require('@/assets/img/buy-comics-subscriptions.png')
            },
            {
                text: 'COMICS SHOP LOCATOR',
                link: '#',
                picture: require('@/assets/img/buy-comics-shop-locator.png')
            },
            {
                text: 'DC POWER VISA',
                link: '#',
                picture: require('@/assets/img/buy-dc-power-visa.svg')
            }
          ]
        }
    }   
}
</script>

<style scoped lang="scss">
div.comics {
    display: flex;
    flex-direction: column;

    #content-main {
        width: 100%;
        background-color: #1c1c1c;
        padding: 50px 0;

        span {
            color: white;
            font-size: 22px;
            font-weight: 600;
        }
    }

    #icons-main {
        padding: 50px 0;
        width: 100%;
        background-color: #0282f9;

        nav {

            ul {
                display: flex;
                list-style: none;

                li {
                    margin: 0 29px;

                    a {
                        display: flex;
                        align-items: center;
                        text-decoration: none;
                        color: #fff;
                        font-size: 14px;

                        img {
                            width: 55px;
                            height: 65px;
                        }

                        span {
                            margin-left: 15px;
                        }
                    }
                }
            }
        }
    }
}
</style>
