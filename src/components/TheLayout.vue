<template>
  <div class="layout">
    <slot></slot>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'TheLayout',
});
</script>

<style>
.layout {
  margin: 0 auto;
  max-width: 1366px;
}
</style>
