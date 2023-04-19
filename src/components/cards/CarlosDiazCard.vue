<script setup lang="ts">
import { BaseCard } from '@/components/BaseCard';
</script>

<template>
  <BaseCard>
    <div class="d-flex h-screen bg-red-400">
      <h1>Carlos Diaz</h1>
      <h4>Car shop</h4>

      <div class="max-w-sm rounded-lg border border-gray-200 bg-white p-6 shadow dark:border-gray-700 dark:bg-gray-800">
        <a href="#">
          <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Mazda miata 2023</h5>
        </a>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">The most seller car in colombia</p>
        <img
          class="rounded-2xl"
          src="https://assets.bridgestonetire.com/content/dam/consumer/bst/la/co/tips/2022/tecnologia-de-llantas/deportivo.jpg"
          alt=""
        />
        <a
          href="#"
          class="mt-4 inline-flex items-center rounded-lg bg-blue-700 px-3 py-2 text-center text-sm font-medium text-white hover:bg-blue-800 focus:outline-none focus:ring-4 focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
        >
          Read more
          <svg
            aria-hidden="true"
            class="-mr-1 ml-2 h-4 w-4"
            fill="currentColor"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
              clip-rule="evenodd"
            ></path>
          </svg>
        </a>
      </div>
    </div>
  </BaseCard>
</template>
