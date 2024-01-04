<script setup lang="ts">
import { RouterView } from 'vue-router'
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'
</script>

<template>
  <div aria-hidden="true" class="fixed right-0 scale-y-[2.5] rotate-45 top-0 w-28 h-96 blur-[5rem] rounded-full bg-indigo-500/30"></div>
  <Header />
  <RouterView />
  <Footer />
</template>
