<template>
  <TheHeader />
  <router-view/>
  <TheFooter />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';

export default defineComponent({
  name: 'App',
  components: {
    TheHeader,
    TheFooter,
  },
});
</script>

<style>
* {
  box-sizing: border-box;
}

html {
  height: calc(100% - 160px);
  background-color: rgb(255, 233, 182);
}

body {
  margin: 0;
  height: 100%;
}

#app {
  height: 100%;
}
</style>
