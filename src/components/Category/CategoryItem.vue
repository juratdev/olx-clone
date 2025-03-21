<template>
  <div class="flex flex-col items-center group cursor-pointer">
    <div
      class="w-20 h-20 rounded-full flex items-center justify-center"
      :style="{ backgroundColor: bgColor }"
    >
      <img :src="icon" alt="icon" class="w-12 h-12" />
    </div>
    <span
      class="mt-2 text-sm font-medium text-gray-900 group-hover:bg-gray-900 group-hover:text-white px-2 transition-all duration-300"
      >{{ title }}</span
    >
  </div>
</template>

<script setup>
defineProps({
  icon: String,
  title: String,
  bgColor: String,
});
</script>
