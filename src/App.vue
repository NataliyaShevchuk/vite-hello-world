<script>
import AppHero from './components/AppHero.vue';
import AppTitle from './components/AppTitle.vue';

    export default {
    components: { AppTitle , AppHero },

    data() {
        return {
          
        };
    },
}
</script>

<template>
  <AppTitle></AppTitle>
  <AppHero></AppHero>
</template>


<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
