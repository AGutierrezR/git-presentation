<script setup lang="ts">
const props = defineProps<{
  value: string
}>()
</script> 

<template>
  <div
    class="h-20 w-50 rounded-xl text-white"
    style="background-image: radial-gradient(farthest-corner at 0 0, var(--tw-gradient-from) 30%, var(--tw-gradient-to))"
  >
    <div
      style="background-image: radial-gradient(farthest-corner at 0 0, var(--tw-gradient-from) 30%, var(--tw-gradient-to))"
      class="absolute w-full h-full from-orange-400 to-red-400 opacity-0 transition duration-400 ease-in pointer-events-none"
    ></div>
    <slot>
      <div class="absolute w-full h-full flex z-10">
        <div class="m-auto text-xl leading-0.8em">
          {{ value }}
        </div>
      </div>
    </slot>
  </div>
</template>