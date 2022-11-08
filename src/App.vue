<script>
import AppBanner from "./components/AppBanner.vue"
export default {

  data() {
    return {
      title: "Mio Titolo"
    }


  },
  components: {
    AppBanner
  }


}
</script>

<template>

  <section>
    <h1>{{title}}</h1>
  </section>
  <AppBanner />

</template>

<style scoped>
</style>