<template>
  <div class="bg-green-800 relative" style="height: 1080px;width: 1920px;">
    <div class="flex justify-center">
      <div class="mt-40 text-gray-100">
        <span class="text-9xl font-extrabold">Simple</span> <br>
        <span class="text-9xl font-extrabold">Quicks</span>
      </div>
    </div>
    <div class="absolute p-2 m-2 bottom-0 right-0 text-right">
      <ChatsEngine />
    </div>
  </div>
</template>

<script setup>
import { defineComponent } from 'vue';
import ChatsEngine from './ChatsEngine.vue';

defineComponent({
  ChatsEngine
})
</script>

