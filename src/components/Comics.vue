<template>
    <div class="comics">
        <section id="content-main">

        </section>
        <section id="icons-main">

        </section>
    </div>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
div.comics {
    display: flex;
    flex-direction: column;

    #content-main {
        width: 100%;
        background-color: #1c1c1c;
        // debug
        height: 150px;
    }

    #icons-main {
        width: 100%;
        background-color: #0282f9;
        // debug
        height: 150px;
    }
}
</style>
