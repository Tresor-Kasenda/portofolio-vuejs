<script setup lang="ts">

</script>

<template>
<div class="mx-auto max-w-6xl py-20">
  <h2 class="text-4xl font-medium">
    Love to hear from you, <br> Get in touch
  </h2><div class="grid grid-cols-3 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-x-8 py-6">
  <div class="p-5 bg-gray-200 rounded space-y-8 border border-indigo-300 mb-8">
    <div class="flex items-center justify-between">
      <div class="flex flex-col gap-2 ">
        <h3 class="text-lg text-indigo-950 font-medium">LinkedIn</h3>
        <a href="" class="text-sm text-indigo-950 font-semibold tracking-wide leading-tight">Tresor kasenda</a>
      </div>
      <img src="" class="h-10 w-10 rounded-full object-cover border-none" alt="">
    </div>
  </div>
  <div class="p-5 bg-gray-200 rounded space-y-8 border border-indigo-300 mb-8">
    <div class="flex items-center justify-between">
      <div class="flex flex-col gap-2 ">
        <h3 class="text-lg text-indigo-950 font-medium">Github</h3>
        <a href=""  class="text-sm text-indigo-950 font-semibold tracking-wide leading-tight">Tresor kasenda</a>
      </div>
      <img src="" class="h-10 w-10 rounded-full object-cover border-none" alt="">
    </div>
  </div>
  <div class="p-5 bg-gray-200 rounded space-y-8 border border-indigo-300 mb-8">
    <div class="flex items-center justify-between">
      <div class="flex flex-col gap-2 ">
        <h3 class="text-lg text-indigo-950 font-medium">Twitter</h3>
        <a href=""  class="text-sm text-indigo-950 font-semibold tracking-wide leading-tight">Tresor kasenda</a>
      </div>
      <img src="" class="h-10 w-10 rounded-full object-cover border-none" alt="">
    </div>
  </div>
</div>
  <div class="w-full bg-red-300 text-white py-3 px-6 font-semibold rounded shadow-sm">
    <span>The field is required</span>
  </div>
  <div class="w-full bg-green-300 text-white py-3 px-6 font-semibold rounded shadow-sm mt-2">
    <span>The field is required</span>
  </div>
  <form action="" @click.prevent="" class="space-y-8">
    <div>
      <div class="space-y-2 py-4">
        <label for="">username</label>
        <input class="w-full px-6 py-4 hover:border-red-500 rounded border border-indigo-500 focus:ring-indigo-300" type="text" name="" id="">
        <span class="text-red-600 tex-sm font-semibold ">The field :fields is required</span>
      </div>
      <div class="space-y-2 py-4">
        <label for="">Email address</label>
        <input class="w-full px-6 py-4 rounded border hover:border-red-500 border-indigo-500 focus:ring-indigo-300" type="text" name="" id="">
        <span class="text-red-600 tex-sm font-semibold ">The field :fields is required</span>
      </div>
      <div class="space-y-2 py-4">
        <label for="">Files</label>
        <input class="w-full px-6 py-4 file:rounded-full fil:px-2 hover:border-red-500 file:text-white file:py-1 file:bg-indigo-400 file:border-none file:ring-indigo-300  file:text-lg border border-indigo-500 " type="file" name="" id="">
        <span class="text-red-600 tex-sm font-semibold ">The field :fields is required</span>
      </div>
      <div class="space-y-2 py-4">
        <label for="">Your prices</label>
        <select class="w-full px-6 py-4 rounded appearance-none border border-indigo-500 hover:border-red-500 focus:ring-indigo-300" name="" id="">
          <option value="">Please select your pricing</option>
          <option value="">500</option>
          <option value="">1000</option>
          <option value="">1500</option>
          <option value="">2000</option>
          <option value="">2500</option>
          <option value="">Customization</option>
        </select>
        <span class="text-red-600 tex-sm font-semibold ">The field :fields is required</span>
      </div>
      <div class="space-y-2 py-4">
        <label for="">Description</label>
        <textarea class="w-full px-6 py-4 rounded hover:border-red-500 border border-indigo-500 focus:ring-indigo-300 placeholder:bg-slate-400" name="" id="" cols="30" rows="10"></textarea>
        <span class="text-red-600 tex-sm font-semibold ">The field :fields is required</span>
      </div>

      <button type="submit" class="bg-indigo-400 gap-x-8 px-5 py-3 rounded text-lg text-white ">
        <span>Just send</span>
      </button>
    </div>

  </form>
</div>
</template>