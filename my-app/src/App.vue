<template>
  <f7-app v-bind="f7params">
    <f7-view main url="/" :routes="routes" class="safe-areas" />
  </f7-app>
</template>

<script setup>
import routes from './routes.js';

const f7params = {
  name: 'TaskFlow',
  id: 'com.taskflow.app',
  theme: 'auto',
  routes,
};
</script>