<script setup lang="ts">
const props = withDefaults(defineProps<{
  image?: string,
  imageClass?: string,
}>(), {
  image: 'https://cover.sli.dev',
  imageClass: '',
})
</script>

<template>
  <div class="grid grid-cols-2 p-0 slidev-layout image-right">
    <div class="flex flex-col justify-center flex-1 p-8">
      <slot />
    </div>
    <div class="relative">
      <div class="absolute z-10 flex items-center h-full p-8">
        <img :src="props.image" class="object-cover rounded shadow-xl" :class="imageClass" />
      </div>
      <div class="absolute top-0 bottom-0 right-0 w-48 bg-gradient-to-tl gradient-primary"></div>
    </div>
  </div>
</template>
