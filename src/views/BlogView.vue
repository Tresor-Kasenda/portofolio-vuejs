<script setup lang="ts">

</script>

<template>
  <section class="py-24 relative">
    <div class="mx-auto max-w-6xl">
      <h1 class="text-4xl font-semibold text-slate-800 ">Articles lists</h1>
      <div class="flex items-center justify-between py-6">
        <div class="space-x-4">
          <a href="#" class="bg-green-500 px-4 py-1 rounded shadow-sm text-white text-sm font-medium ">
            Laravel
          </a>
          <a href="#" class="bg-indigo-500 px-4 py-1 rounded shadow-sm text-white text-sm font-medium ">
            Livewire
          </a>
          <a href="#" class="bg-blue-500 px-4 py-1 rounded shadow-sm text-white text-sm font-medium ">
            Pestphp
          </a>
          <a href="#" class="bg-yellow-500 px-4 py-1 rounded shadow-sm text-white text-sm font-medium ">
            VueJs
          </a>
        </div>
        <div>
          <select name="" id="" class="px-4 py-2 placeholder:bg-gray-500 rounded-md border border-indigo-400 focus:ring-indigo-300 focus:ring-1">
            <option value="">Newest</option>
            <option value="">Latest</option>
          </select>
        </div>
      </div>
      <div class="py-4 ">
        <div class="relative grid grid-cols-3 sm:grid-cols-2 sm:container md:grid-cols-3 lg:grid-cols-3 gap-x-8">
          <div class="bg-gray-200 rounded space-y-4 border shadow border-indigo-300 mb-8">
            <img src="/banner.png" alt="" class="flex-shrink-0 w-full">
            <div class="space-y2 p-5 ">
              <span>Laravel, Livewire, MySQl, AlpineJs</span>
              <h4>Kepasa</h4>
            </div>

          </div>
          <div class="bg-gray-200 rounded space-y-8 border border-indigo-300 mb-8">
            <img src="/banner.png" alt="" class="flex-shrink-0 w-full">
            <div class="space-y2 p-5 ">
              <span>Tailwind css, Figma</span>
              <h4>RoosterCrows</h4>
            </div>
          </div>
          <div class="bg-gray-200 rounded space-y-4 border border-indigo-300 mb-8">
            <img src="/banner.png" alt="" class="flex-shrink-0 w-full">
            <div class="space-y2 p-5 ">
              <span>Tailwind css, AstroJs </span>
              <h4>rc-investment</h4>
            </div>
          </div>

          <div class="bg-gray-200 rounded space-y-4 border border-indigo-300 mb-8">
            <img src="/banner.png" alt="" class="flex-shrink-0 w-full">
            <div class="space-y2 p-5 ">
              <span>Tailwind css, AstroJs </span>
              <h4>Devscast.tech</h4>

            </div>
          </div>

          <div class="bg-gray-200 rounded space-y-4 border border-indigo-300 mb-8">
            <img src="/banner.png" alt="" class="flex-shrink-0 w-full">
            <div class="space-y2 p-5 ">
              <span>Materialize, Angular, Ionic</span>
              <h4>Velocom.be</h4>
            </div>
          </div>
          <div class="bg-gray-200 rounded space-y-4 border border-indigo-300 mb-8">
            <img src="/banner.png" alt="" class="flex-shrink-0 w-full">
            <div class="space-y-2 p-5 ">
              <span>PHP,Boostrap et VueJs</span>
              <h4>Prindustry/White Label Shop</h4>
            </div>
          </div>
          <div class="bg-gray-200 rounded space-y-4 border border-indigo-300 mb-8">
            <img src="/banner.png" alt="" class="flex-shrink-0 w-full">
            <div class="space-y-2 p-5 ">
              <span>PHP,Boostrap et VueJs</span>
              <h4 class="text-lg font-medium tracking-wide">Wikisuite/ Tiki</h4>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>