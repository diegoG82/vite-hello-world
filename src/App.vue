<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  components: {
    AppTitle,
    AppHero,
  },
  data() {
    return {

    }
  }
}
</script>

<template>
  <AppTitle />
  <AppHero />
</template>

<style>
h1 {
  color: cornflowerblue;
  font-style: oblique;
  font-size: 1.5rem;
}
img{
  border: 5px dotted whitesmoke;

}
</style>