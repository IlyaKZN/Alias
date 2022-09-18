<template>
  <main class="main">
    <TheLayout>
    </TheLayout>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import TheLayout from '@/components/TheLayout.vue';

export default defineComponent({
  name: 'StartView',
  components: { TheLayout },
});
</script >

<style scoped>
.main {
  background-color: rgb(255, 242, 252);
  width: 100%;
  height: 100%;
}

p {
  display: block;
}
</style>
