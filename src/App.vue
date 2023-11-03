<script>
import AppHero from './components/AppHero.vue'
export default {

  components: {
    AppHero,
  },

  data() {
    return {
      title: "All'inizio Vite è bello macchinoso!",
    }
  }
}

</script>

<template>
  <div class="title">
    <h1>{{ title }}</h1>
  </div>
  <AppHero />
</template>

<style>
.title {
  color: blueviolet;
  text-align: center;
}
</style>
