<template>
  <div class="flex gap-3">
    <div v-for="server in servers" class="h-[300px] w-[169px] relative cursor-pointer" @mouseover="hover = server.id" @mouseleave="hover = null">
      <img :src="server.src" class="h-full w-full object-cover absolute rounded-md">
      <div class="absolute bottom-0 flex items-center w-full mb-8 flex-col">
      <p class="">{{server.name}}</p>
     <p class="text-gray-400"> {{ server.inGame + ' в игре' }}</p>   
      </div>
      </img>
      <video v-if="hover === server.id" :src="server.videoSrc" class="h-full w-full object-cover absolute rounded-md" autoplay muted ></video>
    </div>
  </div>
      {{ hover }}
      
</template>

<script setup>
let servers = [
  {
    id:1,
    name: "DM",
    inGame: 400,
    src: "DM.webp",
    videoSrc:'DEATHMATCH.mp4',
  },
  {
    id:2,
    name: "DUELS",
    inGame: 228,
    src: "DUELS.webp",
    videoSrc:'DUELS.mp4',
  },
];

let hover = ref(null)
</script>
