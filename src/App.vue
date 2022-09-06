<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <VApp>

    <VMain class="wrapper">

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>

      <VBtn color="primary">Awesome</VBtn>
    </VMain>
  </VApp>

  <RouterView />
</template>
