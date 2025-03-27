<template>
  <nav class="bg-[#002F34] py-4">
    <div class="container px-4 mx-auto flex justify-between items-center">
      <div class="w-16 cursor-pointer max-sm:w-12">
        <img class="w-full" src="/images/logo.svg" alt="logo" />
      </div>
      <div class="flex items-center gap-6 sm:gap-10 max-sm:ml-5">
        <a href="#" class="text-white">
          <i class="fa-regular fa-message"></i>
          <span class="ml-2 hidden sm:inline-block">Chat</span>
        </a>
        <div class="text-white max-sm:text-xs max-sm:flex">
          <a href="#" class="hover:text-gray-300 transition-all duration-300"
            >O'Z</a
          >
          <span class="text-gray-400 mx-2 max-sm:mx-0.5">|</span>
          <a href="#" class="hover:text-gray-300 transition-all duration-300"
            >РУ</a
          >
        </div>
        <a href="#">
          <i
            class="fa-regular fa-heart text-xl max-sm:text-base text-white"
          ></i>
        </a>
        <a href="#">
          <i class="fa-regular fa-bell text-xl max-sm:text-base text-white"></i>
        </a>
        <a href="#" class="text-white">
          <i class="fa-regular fa-user text-xl max-sm:text-base"></i>
          <span class="ml-2 hidden sm:inline">Hisobingiz</span>
        </a>
        <button
          class="text-[#002F34] cursor-pointer border-2 border-transparent hover:border-white hover:text-white hover:bg-[#002F34] bg-white px-3 py-2 rounded font-bold transition-all duration-300 sm:px-4 sm:py-3 max-sm:px-3 max-sm:py-2 max-sm:text-xs"
        >
          E‘lon berish
        </button>
      </div>
    </div>
  </nav>
</template>

<script setup></script>

<style scoped></style>
