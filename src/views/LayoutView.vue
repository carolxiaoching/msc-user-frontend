<template>
  <NavbarComponent />
  <main class="main" :class="{ 'container-lg': $route.name !== 'home' }">
    <RouterView />
  </main>
  <FooterComponent />
</template>

<script setup>
import NavbarComponent from '@/components/NavbarComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';
</script>
