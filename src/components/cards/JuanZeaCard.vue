<script setup lang="ts">
import { BaseCard } from '@/components/BaseCard';

const showDesc = () => {
  alert(
    'La obra es una representación magistral de un disco de vinilo giratorio, que parece cobrar vida bajo la luz que incide en él.'
  );
};
</script>

<template>
  <BaseCard>
    <div class="flex h-full cursor-default flex-col gap-2 overflow-y-auto bg-red-500 p-4">
      <div class="flex justify-center">
        <img
          class="w-32 animate-spin rounded-full"
          src="https://us.123rf.com/450wm/maljuki/maljuki1507/maljuki150700074/42544367-disco-de-vinilo-aislado-en-el-fondo-blanco.jpg?ver=6"
          alt="cat"
        />
      </div>
      <div class="flex flex-col gap-2">
        <h2 class="text-center font-bold text-red-100">El Disco de Vinilo Giratorio</h2>
        <div class="flex justify-center">
          <button class="border border-gray-500 bg-gray-200 px-2" @click="showDesc">Mostrar descripción</button>
        </div>
        <div class="flex justify-end">
          <a
            href="https://github.com/JuanZea"
            target="_blank"
            class="text-red-100 underline duration-75 hover:font-bold hover:text-white"
            >Autor: JuanZea</a
          >
        </div>
      </div>
    </div>
  </BaseCard>
</template>
