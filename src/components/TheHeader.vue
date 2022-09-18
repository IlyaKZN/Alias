<template>
  <header class="header">
    <p class="appName">ALIAS</p>
  </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'TheHeader',
});
</script>

<style>
.header {
  width: 100%;
  height: 80px;
  background-color: rgb(252, 208, 11);
  display: flex;
  align-items: center;
  justify-content: center;
  border-bottom: 2px solid red;
}

.appName {
  margin: 0;
  font-size: 40px;
  font-weight: 400;
  color: #ff0000;
}
</style>
