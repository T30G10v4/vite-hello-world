<script>

export default {

    name: "AppBanner",
    data() {

        return {

            title: "Banner Title",
            imgName: "4ll1s0n.png"

        }
    },
    methods: {

        getImagePath(imgPath) {

            return new URL(imgPath, import.meta.url).href;

        }

    }
}

</script>

<template>

    <section>
       <img :src="getImagePath(`../assets/img/${this.imgName}`)" alt="">
    </section>

</template>

<style scoped>
</style>