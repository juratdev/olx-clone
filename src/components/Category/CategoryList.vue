<template>
  <div class="text-center pt-10 container px-4 mx-auto">
    <h2 class="text-2xl font-bold mb-8">OLX e’lonlar taxtasidagi ruknlar</h2>
    <div
      class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 xl:grid-cols-9 gap-6"
    >
      <CategoryItem
        v-for="(category, index) in categories"
        :key="index"
        :icon="category.icon"
        :title="category.title"
        :bgColor="category.bgColor"
      />
    </div>
  </div>
</template>

<script setup>
import CategoryItem from "./CategoryItem.vue";
import { categories } from "@/data/categories.js";
</script>

<style scoped></style>
