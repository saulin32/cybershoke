<template>
  <div class="flex items-center justify-between  h-full">
    <div class="flex items-center h-full gap-6">
         <div class="flex items-center h-8 font-medium text-sm">
                <div class="bg-[#2C377A] h-full w-8 flex justify-center items-center">
            <img src="../public/cs2.svg" class="h-4"></img>
        </div>
        <div class="bg-[#384161] h-full px-4 flex justify-center items-center">
            <p>CS2</p>
            <img src="../public/arrow.svg" class="w-3 ml-1"></img>
        </div>
    </div>
    <div class="flex items-center h-8 gap-4">
        <button class="flex items-center gap-2">
        <img src="../public/missions-1.svg" />
        <p>0/5</p>
    </button>
    <button class="flex items-center gap-2">
        <img src="../public/drops.svg" />
        <p>0/1</p>
    </button>
    </div>
    <div class="h-8 flex items-center">
        <button class="h-full border border-[#fdb510] text-[#fdb510] rounded-md px-[15px] ">ПОЛУЧИТЬ PREMIUM</button>
    </div>
</div>
    <div class="h-8 flex items-center left-0 gap-[14px]">
    <div class="h-full flex item-center bg-[#1b2229] rounded-md">
    <div class="min-w-9 h-full bg-[#6080ff] rounded-md flex justify-center">
        <img src="../public/online_players.svg" class="w-4 h-full"/>
    </div>
        <p class="flex justify-center">2</p>
    </div>
    <button class="flex items-center px-[10px] bg-[#6080ff] rounded-md h-full"><p>ВОЙТИ ЧЕРЕЗ STEAM</p>
        <img src="../public/steam.svg" class="w-[13px] ml-[7px]"/></button>
    </div>
</div>
</template>

<script setup></script>
