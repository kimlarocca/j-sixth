<script setup>
const currentYear = new Date().getFullYear()
</script>

<template>
  <div class="bg-black p-6">
    <footer class="container text-center">
      <p class="text-white font-semibold text-sm">
        Copyright © {{ currentYear }} JSixth.com. All Rights Reserved.
      </p>
    </footer>
  </div>
</template>
