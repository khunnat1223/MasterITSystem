<template>
  <Navbar/>
  <main class="font-khmer mt-32 mb-8 mx-32">
    <h1 class="text-xl text-center font-bold text-purple-700">អំពីយើង</h1>
      <div class="flex justify-center w-full mt-10">
          <div class="w-1/2">  <img  src="@/assets/image/about1.jpg" alt="Hero Image" class="w-full h-full border-white border-8 object-cover rounded-xl"></div>
          <div class="w-1/2">
            <p class="text-sm">
              តម្រូវការអនាគតឆ្ពោះទៅរកបច្ចេកវិទ្យាឌីជីថលទំនើប និង មើលឃើញពីការលំបាករបស់អាជីវកម្មជាច្រើននៅក្នុងការគ្រប់គ្រងប្រតិបត្តការប្រចាំថ្ងៃ ដែលមានតែភាពមិនច្បាស់លាស់ មិន រលូន មានតែការបាត់បង់ និងមានភាពខ្ជះខ្ជាយ ទាំងនេះជាឧបសគ្គដ៏ធំ រារាំងអាជីវកម្មជាច្រើន មិនអាចរីកចម្រើនបានលឿន ម៉ាស្ទ័រអាយធី ស៊ីស្ទីម ត្រូវបានបង្កើតឡើងដើម្បីឆ្លើយតបលើតម្រូវការ និងដោះស្រាយរាល់បញ្ហា ការលំបាកទាំងអស់នេះរបស់ អាជីវកម្ម ហើយជួយឱ្យអាជីវកម្មអាចគ្រប់គ្រងបានកាន់តែស្រួល កាន់តែច្បាស់ និងរីកចម្រើនកាន់តែលឿន តាមរយៈការបន្ត អភិវឌ្ឍន៍ឥតឈប់ឈរ នូវប្រព័ន្ធបច្ចេកវិទ្យាដែលទំនើប ទាន់សម័យ ស្តង់ដារ សាមញ្ញ ងាយស្រួលប្រើ។</p>
          </div>
      </div>

  </main>
  <Footer/>
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
