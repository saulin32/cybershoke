<template>
  <ListModes
    class="mb-3"
    :modes="
      servers.map((i) => ({
        name: i.name,
      }))
    "
  ></ListModes>
  <ListServers :servers="servers" />
</template>

<script setup>
const route = useRoute();

let servers = [
  {
    id: 1,
    name: "DM",
    inGame: 400,
    src: "DM.webp",
    videoSrc: "DEATHMATCH.mp4",
  },
  {
    id: 2,
    name: "DUELS",
    inGame: 228,
    src: "DUELS.webp",
    videoSrc: "DUELS.mp4",
  },
  {
    id: 3,
    name: "RETAKE",
    inGame: 228,
    src: "RETAKE.webp",
    videoSrc: "RETAKE.mp4",
  },
  {
    id: 3,
    name: "RETAKECARDS",
    inGame: 228,
    src: "RETAKECARDS.webp",
    videoSrc: "RETAKECARDS.mp4",
  },
];
</script>
