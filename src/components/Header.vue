<script lang="ts" setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <header class="border border-b-gray-300 border-dashed w-full">
    <div
      class="hidden lg:flex items-center justify-center bg-indigo-700 p-2 text-center -m-2 text-white text-sm">
      <div>
        <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24"
             xmlns="http://www.w3.org/2000/svg">
          <path
            d="M14.857 17.082a23.848 23.848 0 0 0 5.454-1.31A8.967 8.967 0 0 1 18 9.75V9A6 6 0 0 0 6 9v.75a8.967 8.967 0 0 1-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 0 1-5.714 0m5.714 0a3 3 0 1 1-5.714 0M3.124 7.5A8.969 8.969 0 0 1 5.292 3m13.416 0a8.969 8.969 0 0 1 2.168 4.5"
            stroke-linecap="round"
            stroke-linejoin="round" />
        </svg>
      </div>

      <div class="mt-px ml-1">
        Announcing new feature of our blog,
        <a class="underline decoration-amber-50 decoration-1" href="#">
          Try it now
        </a>
      </div>
    </div>
    <nav class="flex flex-row items-center justify-between  mx-auto max-w-6xl py-6">
      <div>
        <RouterLink class="group flex items-center justify-between" to="/">
          <img alt="" class="w-6 h-6 object-cover hover:rounded-full rounded-3xl" src="">
          <h1 class="pl-2 text-2xl font-bold text-indigo-950 ">
            Tresor Kasenda
          </h1>
        </RouterLink>
      </div>
      <ul class="flex items-center justify-between gap-x-8 sm:hidden md:flex">
        <li>
          <RouterLink class="text-sm font-semibold hover:text-indigo-500 transition duration-300 hover:scale-125"
                      href=""
                      to="/realisation">Realisation
          </RouterLink>
        </li>
        <li>
          <RouterLink class="text-sm font-semibold hover:text-indigo-500 transition duration-300 hover:scale-125"
                      href=""
                      to="/blogs">Blog
          </RouterLink>
        </li>
        <li>
          <RouterLink
            class="group relative px-3 py-2 bg-gray-300 rounded-lg overflow-hidden before:absolute before:inset-0 before:origin-right before:transition before:duration-300 before:bg-gray-800 before:scale-x-0 before:rounded-md hover:before:scale-x-100 hover:before:origin-left"
            href=""
            to="/contact">
            <span class="relative text-sm text-indigo-950 font-semibold group-hover:text-white transition duration-200">Prendre contact</span>
          </RouterLink>
        </li>
      </ul>
    </nav>
  </header>
</template>
