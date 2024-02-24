<template>
    <div class="about">
      <TheWelcome/>
    </div>
  </template>

<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>
  
  <style>
  @media (min-width: 1024px) {
    .about {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }
  }
  </style>
  