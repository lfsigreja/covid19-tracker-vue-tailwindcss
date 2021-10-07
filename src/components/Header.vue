<template>
  <header class="text-center bg-blue-800 text-white p-4 mb10">
    <div class="items-center flex flex-row justify-center text-3xl md:text-5xl font-bold mb-3" >
    <i class="fas fa-disease"></i>
    <p class="ml-4">Covid-19 Tracker</p>
    <!-- <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> -->
    </div>
    <p> API by <a class="text-blue-300" href="https://covid19api.com" target="_blank">covid19api.com</a></p>
  </header>
</template>

<script>
export default {
  name: 'Header',
}
</script>
