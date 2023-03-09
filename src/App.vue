<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about" style="padding-left: 1rem">About - Tu primer componente</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>
