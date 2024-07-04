<template>
  <div class="grid xl:grid-cols-10 md:grid-cols-6 gap-3">
    <div v-for="server in servers" class="h-[300px] max-w-[169px] relative cursor-pointer" @mouseover="hover = server.id" @mouseleave="hover = null">
      <img :src="server.src" class="h-full w-full object-cover absolute rounded-md">
      <div class="absolute bottom-0 flex items-center w-full mb-8 flex-col">
      <p class="">{{server.name}}</p>
     <p class="text-gray-400"> {{ server.inGame + ' в игре' }}</p>   
      </div>
      </img>
      <video v-if="hover === server.id" :src="server.videoSrc" class="h-full w-full object-cover absolute rounded-md" autoplay muted ></video>
    </div>
  </div>
</template>

<script setup>

defineProps(['servers']);
let hover = ref(null)
</script>
