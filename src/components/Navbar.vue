<template>
    <nav class="bg-white shadow-md w-full top-0 fixed z-50">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex justify-between h-28">
          <div class="flex justify-around w-full">
            <div class="flex-shrink-0 flex items-center">
              <img class="h-24 w-auto" src="@/assets/logo.png" alt="Logo" />
              <span class="ml-2 text-purple-800 font-khmer text-xl font-bold">ម៉ាស្ទ័រអាយធី ស៊ីស្ទីម</span>
            </div>
            <div class="hidden sm:-my-px sm:ml-6 sm:flex sm:space-x-8 text-purple-800 font-bold font-khmer">
              <router-link class=" border-transparen inline-flex items-center px-1 pt-1  text-sm " to="/">ទំព័រដើម</router-link>
              <router-link class=" border-transparen inline-flex items-center px-1 pt-1  text-sm " to="/about">អំពីពួកយើង</router-link>
              <router-link class=" border-transparen inline-flex items-center px-1 pt-1  text-sm " to="/service">សេវាកម្ម</router-link>
              <router-link class=" border-transparen inline-flex items-center px-1 pt-1  text-sm " to="/contact">ទំនាក់ទំនង</router-link>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'App'
  }
  </script>