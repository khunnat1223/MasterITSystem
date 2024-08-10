<template>
  <Navbar />

   <div class="bg-purple-800 text-white flex justify-between items-center overflow-hidden">
    <div class="w-1/2 py-52 pl-28 space-y-4">
      <h1 class="text-4xl font-bold mb-4">ម៉ាស្ទ័រអាយធី ស៊ីស្ទឹម</h1>
      <p class="text-yellow-400 font-bold text-xl">ជួយឱ្យអ្នកគ្រប់គ្រងអាជីវកម្មងាយស្រួល និងរីកចម្រើន</p>
      <button class="bg-yellow-400 text-purple-700 font-bold py-2 px-4 rounded-full">
        ទាក់ទងមកពួកយើង
      </button>
    </div>
    <div class="w-1/2 ">
      <div class=" top-0 right-0 bottom-0 left-0 flex items-center justify-center -mr-96">
        <img  src="@/assets/image/image.png" alt="Hero Image" class="w-full h-full border-white border-8 object-cover rounded-full bo">
      </div>
    </div>
  </div>
  <!-- Products -->
  <div class="my-8">
    <h1 class="text-xl font-bold text-center mb-8">ផលិតផលលេចធ្លោ</h1>
      <div class="flex justify-center space-x-4 pb-4">
        <div class="w-64 cursor-pointer">
          <img src="@/assets/image/pic1.jpg" class="w-full h-60 object-cover rounded-md shadow-sm" alt="Product 1">
            <div class="absolute bg-white w-56 shadow-lg rounded-md -mt-14 mx-4 p-2 hover:-mt-16 opacity-95 hover:opacity-100 duration-300">
              <h2 class="text-sm font-semibold">Team Project Plan</h2>
              <p class="text-gray-600 text-xs mt-2 ">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy ...</p>
            </div>
        </div>
        <div class="w-64 cursor-pointer">
          <img src="@/assets/image/pic2.jpg" class="w-full h-60 object-cover rounded-md shadow-sm" alt="Product 1">
            <div class="absolute bg-white w-56 shadow-lg rounded-md -mt-14 mx-4 p-2 hover:-mt-16 opacity-95 hover:opacity-100 duration-300">
              <h2 class="text-sm font-semibold">Techno Logy Business</h2>
              <p class="text-gray-600 text-xs mt-2">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy ...</p>
            </div>
        </div>
        <div class="w-64 cursor-pointer">
          <img src="@/assets/image/pic3.jpg"  class="w-full h-60 object-cover rounded-md shadow-sm" alt="Product 1">
            <div class="absolute bg-white w-56 shadow-lg rounded-md -mt-14 mx-4 p-2 hover:-mt-16 opacity-95 hover:opacity-100 duration-300">
              <h2 class="text-sm font-semibold">Ours Business Technology</h2>
            <p class="text-gray-600 text-xs mt-2">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy ...</p>
            </div>
        </div>
      </div>
  </div>
   <!-- Dai Ku -->
   <div class=" my-8 mt-20 bg-gray-200 p-5">
    <h1 class="text-xl font-bold text-center pb-10">ដៃគូរបស់យើង</h1>
  <div class="grid grid-cols-4 gap-5 px-4 mx-40">
    <div class="flex justify-center items-center mb-10">
      <img src="@/assets/image/logo1.jpg" class="h-20 w-auto grayscale hover:grayscale-0">
    </div>
    <div class="flex justify-center items-center mb-10">
      <img src="@/assets/image/logo2.jpeg" class="h-20 w-auto grayscale hover:grayscale-0">
    </div>
    <div class="flex justify-center items-center mb-10">
      <img src="@/assets/image/logo3.png" class="h-20 w-auto grayscale hover:grayscale-0">
    </div>
    <div class="flex justify-center items-center mb-10">
      <img src="@/assets/image/logo4.png" class="h-20 w-auto grayscale hover:grayscale-0">
    </div>
    <div class="flex justify-center items-center mb-10">
      <img src="@/assets/image/logo5.jpg" class="h-20 w-auto grayscale hover:grayscale-0">
    </div>
    <div class="flex justify-center items-center mb-10">
      <img src="@/assets/image/logo6.png" class="h-20 w-auto grayscale hover:grayscale-0">
    </div>
    <div class="flex justify-center items-center mb-10">
      <img src="@/assets/image/logo7.jpg" class="h-20 w-auto grayscale hover:grayscale-0">
    </div>
  </div>
     
  </div>

  <Footer />

</template>

<script>
import Navbar from '../components/Navbar.vue';
import Footer from '../components/Footer.vue';

export default {
  name: 'HomeView',
  components: {
    Navbar,
    Footer
  }
}
</script>
