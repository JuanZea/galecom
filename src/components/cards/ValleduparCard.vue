<script setup lang="ts">
import { BaseCard } from '@/components/BaseCard';
</script>

<template>
  <BaseCard>
    <nav class="top-0 flex h-max w-full items-center justify-between bg-gray-200">
      <div class="flex flex-col items-center justify-center">
        <h2 class="text-xl text-black">Aplicación prueba</h2>
        <span class="text-black">Tailwindcss + Vue</span>
      </div>
      <div class="flex items-center justify-center">
        <span class="text-black">Aplicación prueba</span>
        <span class="text-black">Tailwindcss + Vue</span>
      </div>
    </nav>
    <div class="mt-5 rounded bg-white p-5 shadow">
      <img
        class="rounded-md shadow-md"
        src="https://img.theculturetrip.com/wp-content/uploads/2018/02/065ed-1.jpg"
        alt=""
      />
      <span class="mt-5 text-xl font-bold text-black"> Valledupar capital mundial del vallenato </span>
    </div>
  </BaseCard>
</template>
