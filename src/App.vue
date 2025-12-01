<template>
  <div class="min-h-screen bg-gray-100">
    <Navbar />
    <div class="p-6">
      <Dashboard />
    </div>
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue';
import Dashboard from './components/Dashboard.vue';
</script>