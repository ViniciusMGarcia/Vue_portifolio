<template>
  <div class="min-h-screen flex flex-col">
    <Header />


    <router-view class="flex-grow" />

    <Footer />
  </div>
</template>

<script setup>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>
