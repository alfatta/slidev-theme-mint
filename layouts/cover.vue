<script setup lang="ts">
const props = withDefaults(defineProps<{
  image?: string,
}>(), {
  image: 'https://cover.sli.dev',
})
</script>

<template>
  <div class="grid grid-cols-2 gap-8 p-0 slidev-layout cover bg-gradient-to-tr gradient-primary">
    <div class="relative">
      <img
        class="absolute bottom-0 right-0 object-cover w-5/6 px-10 pt-10 border-t border-r border-black/50 aspect-[4/5]"
        :src="props.image" />
    </div>
    <div class="w-full my-auto [&_h1]:text-7xl [&_h1]:font-bold [&_p]:font-thin [&_p]:text-3xl">
      <slot />
    </div>
  </div>
</template>