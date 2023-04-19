<script setup lang="ts">
import { BaseCard } from '@/components/BaseCard';
</script>

<template>
  <BaseCard>
    <div class="rounded-lg bg-white shadow-lg">
      <img
        src="https://softmanagement.com.co/antigua/wp-content/uploads/2022/02/future-artificial-intelligence-robot-cyborg.png"
        alt="Imagen de la tarjeta"
        class="h-48 w-full object-cover"
      />
      <div class="p-4">
        <h3 class="text-lg font-medium text-gray-900">Alejandro</h3>
        <p class="mt-2 text-sm text-gray-500">Prueba de creacion de un componente con VUE y Tailwind</p>
      </div>
      <div class="bg-gray-100 px-4 py-2">
        <div>
          <card
            title="Alejandro"
            description="Prueba de creacion de un componente con VUE y Tailwind"
            image-src="https://softmanagement.com.co/antigua/wp-content/uploads/2022/02/future-artificial-intelligence-robot-cyborg.png"
          >
            <button class="rounded bg-blue-500 px-4 py-2 font-bold text-white hover:bg-blue-700">Acción</button>
          </card>
        </div>
      </div>
    </div>
  </BaseCard>
</template>
