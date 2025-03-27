<template>
  <div class="bg-gray-100">
    <div
      class="flex items-center container px-4 mx-auto pb-10 pt-14 rounded-lg"
    >
      <div
        class="flex items-center bg-white px-4 py-6 max-sm:py-4 rounded-l-lg flex-1 sm:flex-[10]"
      >
        <i class="fa-solid fa-magnifying-glass"></i>
        <input
          type="text"
          placeholder="Nimani qidiryapsiz?"
          class="ml-2 outline-none w-full text-[#002F34]"
        />
      </div>

      <div class="w-[1px] h-full bg-gray-300"></div>

      <div
        class="items-center px-4 py-6 bg-white flex-1 sm:flex-[3] hidden md:flex"
      >
        <i class="fa-solid fa-location-dot"></i>
        <span class="ml-2 text-[#002F34]">Oʻzbekiston</span>
      </div>

      <button
        class="flex items-center bg-[#002F34] text-white px-6 py-6 rounded-r-lg font-bold cursor-pointer max-sm:py-5"
      >
        <span class="hidden md:block">Qidiruv</span>
        <i class="fa-solid fa-magnifying-glass ml-2"></i>
      </button>
    </div>
  </div>
</template>

<script setup></script>

<style scoped></style>
