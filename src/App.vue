<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  name: 'AppVue',
  data() {
    return {};
  },
  components: {
    AppTitle,
    AppHero,
  },
};
</script>

<template>
  <AppHero />
  <AppTitle />
</template>

<style scoped></style>
