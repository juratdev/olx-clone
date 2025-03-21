<template>
  <nav class="bg-[#002F34] py-4">
    <div class="container px-4 mx-auto flex justify-between items-center">
      <div class="w-16 cursor-pointer">
        <img class="w-full" src="/images/logo.svg" alt="logo" />
      </div>
      <div class="flex items-center gap-10">
        <a href="#" class="text-white">
          <i class="fa-regular fa-message"></i>
          <span class="ml-2">Chat</span>
        </a>
        <div class="text-white">
          <a href="#" class="hover:text-gray-300 transition-all duration-300"
            >O'Z</a
          >
          <span class="text-gray-400 mr-2 ml-2">|</span>
          <a href="#" class="hover:text-gray-300 transition-all duration-300"
            >РУ</a
          >
        </div>
        <a href="#"> <i class="fa-regular fa-heart text-xl text-white"></i> </a>
        <a href="#">
          <i class="fa-regular fa-bell text-xl text-white"></i>
        </a>
        <a href="#" class="text-white">
          <i class="fa-regular fa-user text-xl"></i>
          <span class="ml-2">Hisobingiz</span>
        </a>
        <button
          class="text-[#002F34] cursor-pointer border-2 border-transparent hover:border-white hover:text-white hover:bg-[#002F34] bg-white px-3 py-2 rounded font-bold transition-all duration-300"
        >
          E‘lon berish
        </button>
      </div>
    </div>
  </nav>
</template>

<script setup></script>

<style scoped></style>
