<script setup>
import { RouterLink, RouterView } from "vue-router";
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
  <!-- <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" /> -->

    <!-- <nav class="bg-white border-gray-200 dark:bg-gray-900">
                            <RouterLink to="/">Home</RouterLink>
                            <RouterLink to="/about">About</RouterLink>
                          </nav> -->

    <nav class="bg-blue-500 p-4">
      <div class="container mx-auto flex justify-between items-center">
        <!-- Logo -->
        <RouterLink to="/" class="text-white text-lg font-semibold hover:bg-blue-600 ">Portfolio</RouterLink>

        <!-- Liens de navigation -->
        <div class="">
          <RouterLink to="/" class="text-white p-4 hover:bg-blue-600">Home</RouterLink>
          <RouterLink to="/about" class="text-white p-4 hover:bg-blue-600">About</RouterLink>
          <!-- TODO Contact -->
          <a href="#" class="text-white p-4 hover:bg-blue-600">Contact</a>
        </div>
      </div>
    </nav>
  </header>

  <RouterView />
</template>
