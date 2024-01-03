<script setup lang="ts">
import {RouterLink} from 'vue-router'
</script>

<template>
  <main class="relative">
    <div class="mx-auto max-w-5xl sm:max-w-3xl md:max-w-4xl lg:max-w-5xl py-24">
      <div class="flex flex-col mx-auto space-y-2">
        <img src="" alt="" class="w-8 h-8 rounded-full object-cover mx-auto ">
        <span class="text-center font-normal text-lg tracking-wide leading-loose">Tresor kasenda</span>
        <span class="text-center font-semibold text-lg tracking-wide leading-loose cursor-pointer text-indigo-600">contact@tresorkasenda.tech</span>
      </div>

      <h1 class="text-6xl leading-tight text-center tracking-wide font-bold font-sans py-10">
        Je suis Developpeur <br> FullStack, Conferencieux
      </h1>
      <div class="flex mx-auto items-center gap-x-8 w-max py-8">
        <RouterLink
          to="/contact"
          class="bg-white border border-slate-300 px-6 py-2 rounded-lg shadow-2xl text-lg font-thin hover:bg-indigo-100 duration-200 ease-in-out hover:border-indigo-300"
          >Nous contactez</RouterLink>
        <a
          href="#"
          class="bg-indigo-500 border-none px-6 py-2 rounded-lg shadow-2xl text-lg font-thin tracking-wide text-white"
          >Github</a>
      </div>
    </div>

    <div class="mx-auto max-w-6xl">
      <div class="py-10">
        <span class="bg-indigo-300 px-4 py-2 rounded shadow text-white font-medium">Mes realisations</span>
        <h2 class="text-4xl font-semibold py-5 tracking-wide">Services</h2>
      </div>

      <div class="grid grid-cols-3 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-x-8">
        <div class="px-4 py-3 bg-indigo-300 rounded space-y-8 border border-indigo-300 mb-8">
          <img src="/Laravel-Logo.wine.png" class="w-12 h-12 object-cover" alt="">
          <span>Backend Laravel, AdonisJs ou NestJs</span>
          <p>
            Je developpe des applications depuis plus de 5 et je maitrise les framework Laravel, AdonisJs et NestJs
          </p>
        </div>
        <div class="px-4 py-3 bg-indigo-300 rounded space-y-8 border border-indigo-300 mb-8">
          <img src="/Vue.js-Logo.wine.png" class="w-12 h-12 object-cover" alt="">
          <span>Fronted VueJs ou ReactJs</span>
          <p>
            Si vous avez besoin d'un developpeur VueJs, ReactJs ou Angular, je maitrise les frameworks et je suis a votre disposition
          </p>
        </div>
        <div class="px-4 py-3 bg-indigo-300 rounded space-y-8 border border-indigo-300 mb-8">
          <img src="/banner.png" class="w-12 h-12 object-cover" alt="">
          <span>UX et UI</span>
          <p>
            Je desing des interfaces graphiques intuitive, efficient and facile a utiliser avec Figma
          </p>
        </div>
        <div class="px-4 py-3 bg-indigo-300 rounded space-y-8 border border-indigo-300 mb-8">
          <img src="/banner.png" class="w-12 h-12 object-cover" alt="">
          <span>Stack TALL</span>
          <p>
            Je developpe depuis plus de 3 ans avec le stack Tailwind css, AlpineJs, Laravel et livewire pour des applications des qualites
          </p>
        </div>
      </div>
    </div>

    <div class="mx-auto max-w-6xl py-20">
      <div class="py-10">
        <span class="bg-indigo-300 px-4 py-2 rounded shadow text-white font-medium">Mes Clients</span>
        <h2 class="text-4xl font-semibold py-5 tracking-wide">Projets</h2>
      </div>

      <div class="grid grid-cols-3 sm:grid-cols-2 sm:container md:grid-cols-3 lg:grid-cols-3 gap-x-8">
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
            <span>Tailwind css, Figma</span>
            <h4>RoosterCrows</h4>
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

    <div class="mx-auto max-w-6xl py-20">
      <div class="py-10">
        <span class="bg-indigo-300 px-4 py-2 rounded shadow text-white font-medium">Reseaux Sociaux</span>
        <h2 class="text-4xl font-semibold py-5 tracking-wide">Me retrouver</h2>
      </div>

      <div class="grid grid-cols-3 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-x-8">
        <div class="p-5 bg-indigo-300 rounded space-y-8 border border-indigo-300 mb-8">
          <div class="flex items-center justify-between">
            <div class="flex flex-col gap-2 ">
              <h3>LinkedIn</h3>
              <a href="" ></a>
            </div>
            <img src="" class="h-10 w-10 border-none" alt="">
          </div>
        </div>
        <div class="p-5 bg-indigo-300 rounded space-y-8 border border-indigo-300 mb-8">
          <div class="flex items-center justify-between">
            <div class="flex flex-col gap-2 ">
              <h3>Github</h3>
              <a href="" ></a>
            </div>
            <img src="" class="h-10 w-10 border-none" alt="">
          </div>
        </div>
        <div class="p-5 bg-indigo-300 rounded space-y-8 border border-indigo-300 mb-8">
          <div class="flex items-center justify-between">
            <div class="flex flex-col gap-2 ">
              <h3>Twitter</h3>
              <a href="" ></a>
            </div>
            <img src="" class="h-10 w-10 border-none" alt="">
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
