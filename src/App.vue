<script setup lang="ts">
import { RouterLink, RouterView }  from 'vue-router'
</script>

<template>
  <div>
    <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/inner">Inner</RouterLink>
    </nav>
    <RouterView />
  </div>
</template>

<style scoped>
</style>
