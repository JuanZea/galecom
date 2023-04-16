<script setup lang="ts">
import { BaseCard } from '@/components/BaseCard';
</script>

<template>
  <BaseCard>
    <div class="flex h-full cursor-default flex-col gap-2 overflow-y-auto rounded-lg bg-blue-200 p-4">
      <div>
        <img
          src="https://images.unsplash.com/photo-1609266086311-0dcf0dcc00dc?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"
          alt=""
        />
      </div>
      <div>
        <div class="flex justify-end">
          <a href="https://github.com/JuanZea" target="_blank" class="underline duration-75 hover:font-bold"
            >Laura Torres</a
          >
        </div>
        <h2 class="font-bold">La mirada del gato</h2>
        <p class="">
          Es una obra de arte que captura la esencia enigmática y seductora de un felino. La imagen presenta un primer
          plano del rostro de un gato, con sus ojos amarillos brillantes y suavemente iluminados por la luz. La mirada
          penetrante del gato parece trascender el lienzo, invitando al espectador a adentrarse en su mundo y explorar
          su misteriosa personalidad.
        </p>
      </div>
    </div>
  </BaseCard>
</template>
