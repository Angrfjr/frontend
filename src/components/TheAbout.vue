<template>
  <div>
    <TheNavbar />
    <figure class="relative  bg-auto">
      <img class="rounded-lg  opacity-50" src="../assets/dispen.jpg" alt="Telkom Image">
      <figcaption class="absolute w-screen h-screen justify-center items-center px-4 text-lg text-white top-6">
        <h1
          class="flex justify-center mb-3 text-7xl  font-extrabold tracking-tight text-gray-900 dark:text-white">
          <center>We are here for Helping Resident Data</center>
        </h1>
        <span class="m-2"></span>
        <p class="mb-3 text-3xl font-sans font-medium text-gray-100 dark:text-gray-400">
          <center>Telkom Dikti merupakan Aplikasi buatan kelompok kami yang memiliki fungsi dalam Pencatatan Data Penduduk secara simpel dan mudah untuk digunakan oleh instansi terkait.</center>
        </p>
        <span class="m-2"></span>
      </figcaption>
    </figure>
  </div>
</template>
  
<script>
import TheNavbar from './TheNavbar.vue';
export default {
  nama: "TheAbout",
  components: {
    TheNavbar
  }
}
</script>
  
<style>

</style>