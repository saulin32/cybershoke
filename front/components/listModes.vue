<template>
  <div class="flex gap-1">
    <button
      v-for="mode in modes"
      class="flex justify-center items-center bg-[#1b2229] rounded-md h-10 px-4 text-sm text-[#aecce4] font-medium hover:text-blue-500"
    >
      {{ mode.name }}
    </button>
  </div>
</template>

<script setup>
let modes = [
  {
    name: "EXECUTE",
    src: "",
  },
  {
    name: "DM",
    src: "",
  },
  {
    name: "DUELS",
    src: "",
  },
  {
    name: "RETAKE",
    src: "",
  },
  {
    name: "RETAKE CARDS",
    src: "",
  },
];
</script>
