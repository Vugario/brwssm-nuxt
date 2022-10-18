<template>
  <div class="bg-gray-100 min-h-screen">
    <header class="text-white py-4" style="background: #d0031a">
      <div class="mx-auto max-w-2xl flex justify-between px-3">
        <div>
          <span class="block text-xl">Post Sassenheim</span>
          <span>Brandweer Hollands Midden</span>
        </div>
        <div>Socials go here</div>
      </div>
    </header>
    <nav
      class="hidden md:block bg-white border-t border-b border-gray-300 px-3"
    >
      <div class="mx-auto max-w-2xl">
        <ul>
          <li class="inline-block">
            <a href="#" class="p-3 inline-block hover:text-gray-500"> Home </a>
          </li>
          <li class="inline-block">
            <a href="#" class="p-3 inline-block text-gray-500 hover:text-black">
              Uitrukken
            </a>
          </li>
        </ul>
      </div>
    </nav>

    <div class="mx-auto max-w-2xl my-3 p-3">
      <Nuxt />
    </div>

    <div
      class="fixed bottom-0 left-0 w-full bg-white border-t border-b border-gray-400 flex"
    >
      <div class="flex-1 text-center">
        <NuxtLink to="/" exact class="inline-block w-full p-4 text-gray-400">
          Home
        </NuxtLink>
      </div>
      <div class="flex-1 text-center">
        <NuxtLink class="inline-block w-full p-4 text-gray-400" to="reports"
          >Uitrukken</NuxtLink
        >
      </div>
      <div class="flex-1 text-center">
        <NuxtLink to="p2000" class="inline-block w-full p-4 text-gray-400"
          >P2000</NuxtLink
        >
      </div>
      <div class="flex-1 text-center">
        <NuxtLink to="contact" class="inline-block w-full p-4 text-gray-400"
          >Contact</NuxtLink
        >
      </div>
    </div>
  </div>
</template>
