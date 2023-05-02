<template>
  <navbar />
  <main>
    <div class="max-w-[1200px] mx-auto">
      <router-view />
    </div>
  </main>
  <Footer></Footer>
</template>

<script setup>
import Navbar from "../components/Navbar.vue";
import Footer from "./Footer.vue";
</script>
