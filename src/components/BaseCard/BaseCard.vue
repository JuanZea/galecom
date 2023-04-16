<script setup lang="ts"></script>

<template>
  <div class="flex justify-center">
    <div class="cursor-pointer rounded bg-white p-4 shadow-md">
      <div class="max-h-[1500px] w-80 overflow-hidden md:h-80">
        <slot />
      </div>
    </div>
  </div>
</template>
