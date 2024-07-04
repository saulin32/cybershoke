<template>
  <div class="flex gap-1 flex-wrap justify-center">
    <button
      v-for="mode in modes"
      class="flex justify-center items-center bg-[#1b2229] rounded-md h-10 px-4 text-sm text-[#aecce4] font-medium hover:text-blue-500"
    >
      {{ mode.name }}
    </button>
  </div>
</template>

<script setup>
defineProps(["modes"]);
// let modes = [
//   {
//     name: "EXECUTE",
//     src: "",
//   },
//   {
//     name: "DM",
//     src: "",
//   },
//   {
//     name: "DUELS",
//     src: "",
//   },
//   {
//     name: "RETAKE",
//     src: "",
//   },
//   {
//     name: "RETAKE CARDS",
//     src: "",
//   },
//   {
//     name: "5X5",
//     src: "",
//   },
//   {
//     name: "2X2",
//     src: "",
//   },
//   {
//     name: "BHOP",
//     src: "",
//   },
//   {
//     name: "SURF",
//     src: "",
//   },
//   {
//     name: "KZ",
//     src: "",
//   },
//   {
//     name: "AWP",
//     src: "",
//   },
//   {
//     name: "PUBLIC",
//     src: "",
//   },
//   {
//     name: "DUELS 2X2",
//     src: "",
//   },
//   {
//     name: "ARENA",
//     src: "",
//   },
//   {
//     name: "PISTOLDM",
//     src: "",
//   },
//   {
//     name: "CLUTCH",
//     src: "",
//   },
//   {
//     name: "MANIAC",
//     src: "",
//   },
//   {
//     name: "HSDM",
//     src: "",
//   },
//   {
//     name: "PISTOL RETAKE",
//     src: "",
//   },
//   {
//     name: "AWPDM",
//     src: "",
//   },
//   {
//     name: "MULTICFG",
//     src: "",
//   },
//   {
//     name: "DEATHRUN",
//     src: "",
//   },
//   {
//     name: "MINIGAMES",
//     src: "",
//   },
//   {
//     name: "AIMDM",
//     src: "",
//   },
//   {
//     name: "SURF COMBAT",
//     src: "",
//   },
// ];
</script>
