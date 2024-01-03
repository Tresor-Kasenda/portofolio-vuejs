<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <header class="border border-b-slate-500 w-full">
    <div class="bg-indigo-400 py-2 items-center -m-2">
      <p class="text-white text-center font-medium text-sm">Announcing new feature of our blog, <a href="#" class="underline decoration-amber-50 decoration-1">Try it now</a></p>
    </div>
    <nav class="flex flex-row items-center justify-between  mx-auto max-w-6xl py-6">
      <div>
        <RouterLink to="/" class="group flex items-center justify-between">
          <img src="" alt="" class="w-6 h-6 object-cover hover:rounded-full rounded-3xl">
          <h1 class="pl-2 text-3xl font-bold text-indigo-950 ">
            Tresor Kasenda
          </h1>
        </RouterLink>
      </div>
      <ul class="flex items-center justify-between gap-x-8 sm:hidden md:flex">
        <li>
          <RouterLink to="/realisation" class="text-lg font-semibold hover:text-indigo-500 transition duration-300 hover:scale-125" href="">Realisation</RouterLink>
        </li>
        <li>
          <RouterLink to="/blogs" class="text-lg font-semibold hover:text-indigo-500 transition duration-300 hover:scale-125" href="">Blog</RouterLink>
        </li>
        <li>
          <RouterLink to="/contact" class="group relative px-5 py-3 bg-indigo-400 rounded-md overflow-hidden before:absolute before:inset-0 before:origin-right before:transition before:duration-300 before:bg-indigo-800 before:scale-x-0 hover:before:scale-x-100 hover:before:origin-left" href="">
            <span class="relative text-white font-medium group-hover:text-white transition duration-200">Prendre contact</span>
          </RouterLink>
        </li>
      </ul>
    </nav>
  </header>
</template>
