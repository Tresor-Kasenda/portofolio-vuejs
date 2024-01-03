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
        <div class="grid grid-cols-3 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-x-8">
          <div class="p-5 bg-indigo-300 rounded space-y-8 border border-indigo-300 mb-8">
            <img src="" alt="" class="flex-shrink-0 w-full">
            <div class="space-y-6">
              <span>Laravel, Livewire, MySQl, AlpineJs</span>
              <h4>Kepasa</h4>
              <p class="py-4">
                Developpement Livewire, Laravel, Alpine pour le lancement d'une plateforme de promotion de ville et de billeteries
              </p>
              <a class="bg-indigo-600 px-4 py-2 rounded text-white " href="#">En savoir plus</a>
            </div>
          </div>

          <div class="p-5 bg-indigo-300 rounded space-y-8 border border-indigo-300 mb-8">
            <img src="" alt="" class="flex-shrink-0 w-full">
            <div class="space-y-6">
              <span>Tailwind css, AstroJs </span>
              <h4>rc-investment</h4>
              <p class="py-4">
                Developpement d'un site web vitrine pour une entreprise local
              </p>

              <a class="bg-indigo-600 px-4 py-3 rounded text-white " href="#">En savoir plus</a>
            </div>
          </div>

          <div class="p-5 bg-indigo-300 rounded space-y-8 border border-indigo-300 mb-8">
            <img src="" alt="" class="flex-shrink-0 w-full">
            <div class="space-y-6">
              <span>Tailwind css, AstroJs </span>
              <h4>Devscast.tech</h4>
              <p class="py-4">
                Contribution au developpement de la partie frontend de la version 2 avec AstroJs et Tailwind css
              </p>

              <a class="bg-indigo-600 px-4 py-3 rounded text-white " href="#">En savoir plus</a>
            </div>
          </div>

          <div class="p-5 bg-indigo-300 rounded space-y-8 border border-indigo-300 mb-8">
            <img src="" alt="" class="flex-shrink-0 w-full">
            <div class="space-y-6">
              <span>Materialize, Angular, Ionic</span>
              <h4>Velocom.be</h4>
              <p class="py-4">
                Developpement de la partie frontend de la partie administration en utilisant Angular et Ionic
              </p>

              <a class="bg-indigo-600 px-4 py-3 rounded text-white " href="#">En savoir plus</a>
            </div>
          </div>
          <div class="p-5 bg-indigo-300 rounded space-y-8 border border-indigo-300 mb-8">
            <img src="" alt="" class="flex-shrink-0 w-full">
            <div class="space-y-6">
              <span>PHP,Boostrap et VueJs</span>
              <h4>Prindustry/White Label Shop</h4>
              <p class="py-4">
                J'ai travailler en tant que Mainteneur de cette plateforme en ajoutant des fonctionnalites et en corrigeants des bugs
              </p>

              <a class="bg-indigo-600 px-4 py-3 rounded text-white " href="#">En savoir plus</a>
            </div>
          </div>
          <div class="p-5 bg-indigo-300 rounded space-y-8 border border-indigo-300 mb-8">
            <img src="" alt="" class="flex-shrink-0 w-full">
            <div class="space-y-6">
              <span>PHP,Boostrap et VueJs</span>
              <h4>Wikisuite/ Tiki</h4>
              <p class="py-4">
                J'ai travailler en tant que Mainteneur de cette plateforme en ajoutant des fonctionnalites et en corrigeants des bugs
              </p>

              <a class="bg-indigo-600 px-4 py-3 rounded text-white " href="#">En savoir plus</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>