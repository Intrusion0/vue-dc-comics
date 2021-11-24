<template>
    <div class="comics">
        <section id="content-main">
            <div class="ms-container">
                <span>
                    --&#62; Content goes here &#60;--
                </span>
            </div>
        </section>
        <IconsComics/>
    </div>
</template>

<script>
import IconsComics from './IconsComics.vue'

export default {
  name: 'Comics',
  components: {
      IconsComics
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
}
</style>
