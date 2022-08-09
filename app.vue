<template>
  <div>
    <vueQr :text="code2FA"></vueQr>
    <NuxtWelcome />
  </div>
</template>

<script setup lang="ts">
import vueQr from 'vue-qr/src/packages/vue-qr.vue';
</script>