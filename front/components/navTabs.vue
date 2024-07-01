<template>
  <div class="flex flex-col bg-[#0c101a] h-full items-center py-[14px]">
    <img src="../public/cybershoke.svg" alt="sybershoke" class="w-[42px]"></img>
    <div class="flex flex-col justify-center gap-[30px] h-full items-center">
        <NuxtLink class="flex flex-col items-center text-xs text-gray-400 group" v-for="tab in tabs" to="/">
            <img :src="tab.src" :alt="tab.alt" class="w-[20px] group-hover:scale-[1.1]"></img>
            <p>{{ tab.name }}</p>
        </NuxtLink>
    </div>
  </div>
</template>

<script setup>

let tabs = [
    {
        name:'Играть',
        src:'play.svg',
        alt:'sybershoke',
    },
    {
        name:'PREMIUM',
        src:'premium.svg',
        alt:'sybershoke',
    },
    {
        name:'Миссии',
        src:'missions.svg',
        alt:'sybershoke',
    },
    {
        name:'Лидерборд',
        src:'leaderboard.svg',
        alt:'',
    },
    {
        name:'Магазин',
        src:'shop.svg',
        alt:'',
    },
    {
        name:'Помощь',
        src:'help.svg',
        alt:'',
    },
    {
        name:'Сервисы',
        src:'service.svg',
        alt:'',
    },
]
</script>
