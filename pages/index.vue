<template>
  <div>
    <!--<div class="border-b border-gray-200 mb-3">
      <nav class="flex space-x-4">
        <a
          href="#"
          class="border-transparent border-b-2 text-gray-500 whitespace-nowrap py-2 px-1"
        >
          Recente berichten
        </a>
        <a
          href="#"
          class="border-gray-600 border-b-2 text-gray-600 whitespace-nowrap py-2 px-1"
        >
          Recente uitrukken
        </a>
      </nav>
    </div>-->
    <div class="pb-2">Instagram</div>
    <div class="grid grid-cols- gap-3">
      <div class="bg-white shadow mb-3">
        <img
          src="https://scontent.cdninstagram.com/v/t51.29350-15/311777164_187741053752741_4885811737982354860_n.webp?stp=dst-jpg&_nc_cat=104&ccb=1-7&_nc_sid=8ae9d6&_nc_ohc=jAn1_qVjvIUAX_TObZ1&_nc_ht=scontent.cdninstagram.com&edm=ANo9K5cEAAAA&oh=00_AT_XYatdWtwSIYEJal9qhPpY9ajeP4vU-UBsutLCYZkfjA&oe=63529D47"
        />
        <div class="p-3 text-sm">
          P2 Assistentie ambulance Vijmeiweg Sassenheim 161152 161230 9.38 uur
          18/10/22 🚒 Wij assisteerden de ambulancedienst met het afhijsen van
          een patiënt samen met @brandweerlisse. #SassemParaat
          <div class="text-xs mt-3">
            <a href="#" class="underlined md:hover:text-gray-500"
              >BrandweerSSM</a
            >
            <span class="text-gray-500 whitespace-nowrap">3 hours ago</span>
          </div>
        </div>
      </div>
      <div class="bg-white shadow mb-3">
        <img
          src="https://scontent.cdninstagram.com/v/t51.29350-15/311777164_187741053752741_4885811737982354860_n.webp?stp=dst-jpg&_nc_cat=104&ccb=1-7&_nc_sid=8ae9d6&_nc_ohc=jAn1_qVjvIUAX_TObZ1&_nc_ht=scontent.cdninstagram.com&edm=ANo9K5cEAAAA&oh=00_AT_XYatdWtwSIYEJal9qhPpY9ajeP4vU-UBsutLCYZkfjA&oe=63529D47"
        />
        <div class="p-3 text-sm">
          P2 Assisentie ambulance Vijmeiweg Sassenheim
          <div class="text-xs mt-2">
            <a href="#" class="underlined md:hover:text-gray-500"
              >BrandweerSSM</a
            >
            <span class="text-gray-500 whitespace-nowrap">3 hours ago</span>
          </div>
        </div>
      </div>
    </div>

    <div class="grid grid-cols-3 gap-4">
      <div class="col-span-3 md:col-span-2">
        <div class="divide-y divide-gray-200 bg-white shadow">
          <div class="p-3">Header</div>
          <div class="p-3">Body</div>
        </div>
      </div>
      <div class="hidden md:block md:col-span-1">Sidebar</div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
})
</script>
