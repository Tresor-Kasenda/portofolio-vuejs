<script lang="ts" setup>
import { RouterLink } from 'vue-router'
import SpanComponent from '@/components/molecules/span-component.vue'
</script>

<template>
  <main class="relative">
    <div class="mx-auto max-w-5xl sm:max-w-3xl md:max-w-4xl lg:max-w-5xl py-20">
      <h1 class="text-4xl leading-tight text-center font-bold font-sans py-8">
        Est un Developpeur <br> FullStack, Speaker,Open Source
      </h1>
      <div class="flex mx-auto items-center gap-x-6 w-max py-6">
        <RouterLink
          class="bg-white border border-slate-300 px-5 py-2 rounded-lg shadow-2xl text-sm font-semibold hover:bg-indigo-100 duration-200 ease-in-out hover:border-indigo-300"
          to="/contact"
        >Nous contactez
        </RouterLink>
        <a
          class="bg-indigo-500 px-5 py-2 rounded-lg shadow-2xl text-sm font-thin tracking-wide text-white"
          href="#"
        >Github</a>
      </div>
      <div class="flex justify-center pt-3 items-center mx-auto text-white gap-x-8">
        <img alt="" class="bg-transparent" src="/icons/logos.svg">
      </div>
    </div>

    <div class="mx-auto max-w-6xl">
      <div class="py-10">
        <span-component>Mes realisations</span-component>
        <h2 class="text-4xl font-semibold py-5 tracking-wide">Services</h2>
      </div>

      <div class="grid grid-cols-3 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-x-8">
        <div
          class="px-4 py-3 bg-gray-200 hover:bg-gray-100 transition duration-300 ease-in-out hover:rounded-2xl hover:shadow rounded space-y-8 border border-indigo-300 mb-8">
          <img alt="" class="w-12 h-12 object-cover" src="/Laravel-Logo.wine.png">
          <span class="text-nowrap text-lg font-medium text-indigo-950">Backend Laravel, AdonisJs ou NestJs</span>
          <p class="text-sm tracking-wide leading-loose">
            Je developpe des applications depuis plus de 5 et je maitrise les framework Laravel, AdonisJs et NestJs
          </p>
        </div>
        <div
          class="px-4 py-3 bg-gray-200 hover:bg-gray-100 transition duration-300 ease-in-out hover:rounded-2xl hover:shadow rounded space-y-8 border border-indigo-300 mb-8">
          <img alt="" class="w-12 h-12 object-cover" src="/Vue.js-Logo.wine.png">
          <span class="text-nowrap text-lg font-medium text-indigo-950">Fronted VueJs ou ReactJs</span>
          <p class="text-sm tracking-wide leading-loose">
            Si vous avez besoin d'un developpeur VueJs, ReactJs ou Angular, je maitrise les frameworks et je suis a
            votre disposition
          </p>
        </div>
        <div
          class="px-4 py-3 bg-gray-200 hover:bg-gray-100 transition duration-300 ease-in-out hover:rounded-2xl hover:shadow rounded space-y-8 border border-indigo-300 mb-8">
          <img alt="" class="w-12 h-12 object-cover" src="/banner.png">
          <span class="text-nowrap text-lg font-medium text-indigo-950">UX et UI</span>
          <p class="text-sm tracking-wide leading-loose">
            Je desing des interfaces graphiques intuitive, efficient and facile a utiliser avec Figma
          </p>
        </div>
        <div
          class="px-4 py-3 bg-gray-200 hover:bg-gray-100 transition duration-300 ease-in-out hover:rounded-2xl hover:shadow rounded space-y-8 border border-indigo-300 mb-8">
          <img alt="" class="w-12 h-12 object-cover" src="/banner.png">
          <span class="text-nowrap text-lg font-medium text-indigo-950">Stack TALL</span>
          <p class="text-sm tracking-wide leading-loose">
            Je developpe depuis plus de 3 ans avec le stack Tailwind css, AlpineJs, Laravel et livewire pour des
            applications des qualites
          </p>
        </div>
      </div>
    </div>

    <div class="relative mx-auto max-w-6xl py-20">
      <div
        class="absolute -top-10 left-1/2 -translate-x-1/2 bg-gradient-to-bl from-indigo-700/10 to-green-500/20 w-4/5 max-w-3xl h-4/6 rounded-t-full flex blur-3xl"></div>
      <div class="py-10 relative">
        <span-component>Mes clients</span-component>
        <h2 class="text-4xl font-semibold py-5 tracking-wide">Projets</h2>
      </div>

      <div class="relative grid grid-cols-3 sm:grid-cols-2 sm:container md:grid-cols-3 lg:grid-cols-3 gap-x-8">
        <div class="bg-gray-200 rounded space-y-8 border shadow border-indigo-300 mb-8">
          <img alt="" class="flex-shrink-0 w-full" src="/banner.png">
          <div class="space-y-6 p-5 ">
            <span>Laravel, Livewire, MySQl, AlpineJs</span>
            <h4>Kepasa</h4>
            <p class="py-4">
              Developpement Livewire, Laravel, Alpine pour le lancement d'une plateforme de promotion de ville et de
              billeteries
            </p>
            <a class="bg-indigo-600 px-4 py-2 rounded text-white " href="#">En savoir plus</a>
          </div>

        </div>
        <div class="bg-gray-200 rounded space-y-8 border border-indigo-300 mb-8">
          <img alt="" class="flex-shrink-0 w-full" src="/banner.png">
          <div class="space-y-6 p-5 ">
            <span>Tailwind css, Figma</span>
            <h4>RoosterCrows</h4>
            <p class="py-4">
              Developpement d'un site web vitrine pour une entreprise local
            </p>

            <a class="bg-indigo-600 px-4 py-3 rounded text-white " href="#">En savoir plus</a>
          </div>
        </div>
        <div class="bg-gray-200 rounded space-y-8 border border-indigo-300 mb-8">
          <img alt="" class="flex-shrink-0 w-full" src="/banner.png">
          <div class="space-y-6 p-5 ">
            <span>Tailwind css, AstroJs </span>
            <h4>rc-investment</h4>
            <p class="py-4">
              Developpement d'un site web vitrine pour une entreprise local
            </p>

            <a class="bg-indigo-600 px-4 py-3 rounded text-white " href="#">En savoir plus</a>
          </div>
        </div>

        <div class="bg-gray-200 rounded space-y-8 border border-indigo-300 mb-8">
          <img alt="" class="flex-shrink-0 w-full" src="/banner.png">
          <div class="space-y-6 p-5 ">
            <span>Tailwind css, AstroJs </span>
            <h4>Devscast.tech</h4>
            <p class="py-4">
              Contribution au developpement de la partie frontend de la version 2 avec AstroJs et Tailwind css
            </p>

            <a class="bg-indigo-600 px-4 py-3 rounded text-white " href="#">En savoir plus</a>
          </div>
        </div>

        <div class="bg-gray-200 rounded space-y-8 border border-indigo-300 mb-8">
          <img alt="" class="flex-shrink-0 w-full" src="/banner.png">
          <div class="space-y-6 p-5 ">
            <span>Materialize, Angular, Ionic</span>
            <h4>Velocom.be</h4>
            <p class="py-4">
              Developpement de la partie frontend de la partie administration en utilisant Angular et Ionic
            </p>

            <a class="bg-indigo-600 px-4 py-3 rounded text-white " href="#">En savoir plus</a>
          </div>
        </div>
        <div class="bg-gray-200 rounded space-y-8 border border-indigo-300 mb-8">
          <img alt="" class="flex-shrink-0 w-full" src="/banner.png">
          <div class="space-y-6 p-5 ">
            <span>PHP,Boostrap et VueJs</span>
            <h4>Prindustry/White Label Shop</h4>
            <p class="py-4">
              J'ai travailler en tant que Mainteneur de cette plateforme en ajoutant des fonctionnalites et en
              corrigeants des bugs
            </p>

            <a class="bg-indigo-600 px-4 py-3 rounded text-white " href="#">En savoir plus</a>
          </div>
        </div>
        <div class="bg-gray-200 rounded space-y-8 border border-indigo-300 mb-8">
          <img alt="" class="flex-shrink-0 w-full" src="/banner.png">
          <div class="space-y-2 p-5 ">
            <span>PHP,Boostrap et VueJs</span>
            <h4 class="text-lg font-medium tracking-wide">Wikisuite/ Tiki</h4>
            <p class=" leading-normal text-sm  pb-4">
              J'ai travailler en tant que Mainteneur de cette plateforme en ajoutant des fonctionnalites et en
              corrigeants des bugs
            </p>
            <a class="bg-indigo-600 px-4 py-2 rounded border-none text-white " href="#">En savoir plus</a>
          </div>
        </div>
      </div>
    </div>

    <div class="mx-auto max-w-6xl py-20">
      <div class="py-10">
        <span-component>Reseaux sociaux</span-component>
        <h2 class="text-4xl font-semibold py-5 tracking-wide">Me retrouver</h2>
      </div>

      <div class="grid grid-cols-3 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-x-8">
        <div class="p-5 bg-gray-200 rounded space-y-8 border border-indigo-300 mb-8">
          <div class="flex items-center justify-between">
            <div class="flex flex-col gap-2 ">
              <h3 class="text-lg text-indigo-950 font-medium">LinkedIn</h3>
              <a class="text-sm text-indigo-950 font-semibold tracking-wide leading-tight" href="">Tresor kasenda</a>
            </div>
            <img alt="" class="h-10 w-10 rounded-full object-cover border-none" src="">
          </div>
        </div>
        <div class="p-5 bg-gray-200 rounded space-y-8 border border-indigo-300 mb-8">
          <div class="flex items-center justify-between">
            <div class="flex flex-col gap-2 ">
              <h3 class="text-lg text-indigo-950 font-medium">Github</h3>
              <a class="text-sm text-indigo-950 font-semibold tracking-wide leading-tight" href="">Tresor kasenda</a>
            </div>
            <img alt="" class="h-10 w-10 rounded-full object-cover border-none" src="">
          </div>
        </div>
        <div class="p-5 bg-gray-200 rounded space-y-8 border border-indigo-300 mb-8">
          <div class="flex items-center justify-between">
            <div class="flex flex-col gap-2 ">
              <h3 class="text-lg text-indigo-950 font-medium">Twitter</h3>
              <a class="text-sm text-indigo-950 font-semibold tracking-wide leading-tight" href="">Tresor kasenda</a>
            </div>
            <img alt="" class="h-10 w-10 rounded-full object-cover border-none" src="">
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
