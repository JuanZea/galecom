<script setup lang="ts">
import {
  JuanZeaCard,
  LauraTorresCard,
  CarlosDiazCard,
  RogelioCard,
  AlejandroCard,
  ValleduparCard,
} from '@/components/cards';
</script>

<template>
  <div class="h-full min-h-screen bg-gray-200">
    <div class="container mx-auto flex flex-col gap-2 pb-10 pt-4">
      <div class="flex items-center">
        <img class="mt-1 h-10 fill-gray-700" src="/src/assets/panorama.svg" alt="panorama" />
        <h1 class="text-4xl text-gray-700">Galecom</h1>
      </div>
      <hr class="border-2 border-gray-500" />
      <div class="grid grid-cols-1 gap-8 px-8 md:grid-cols-2 xl:grid-cols-3">
        <JuanZeaCard />
        <CarlosDiazCard />
        <RogelioCard />
        <AlejandroCard />
        <ValleduparCard />
        <LauraTorresCard />
      </div>
    </div>
  </div>
</template>
