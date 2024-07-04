<template>
  <div class="flex items-center justify-between  h-full">
    <div class="flex items-center h-full gap-6">
         <button class="flex items-center h-8 font-medium text-sm">
                <div class="bg-[#2C377A] h-full w-8 flex justify-center items-center">
            <img src="../public/cs2.svg" class="h-4"></img>
        </div>
        <div class="bg-[#384161] h-full px-4 flex justify-center items-center">
            <p>CS2</p>
            <img src="../public/arrow.svg" class="w-3 ml-1"></img>
        </div>
    </button>
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
    <button class="h-full flex items-center bg-[#1b2229] rounded-md">
    <div class="min-w-9 h-full bg-[#6080ff] rounded-md flex justify-center ">
        <img src="../public/online_players.svg" class="w-4 h-full"/>
    </div>
    <div class="flex items-center m-2 gap-1">
        <p >2</p>
        <svg xmlns="http://www.w3.org/2000/svg" width="8" height="16" viewBox="0 0 8 16" fill="none"><path d="M3.99995 9.99962C3.82319 9.99958 3.65368 9.92933 3.52871 9.80432L0.862545 7.13816C0.798883 7.07668 0.748105 7.00313 0.713172 6.92181C0.678239 6.84049 0.659852 6.75302 0.659083 6.66452C0.658314 6.57602 0.675178 6.48825 0.708692 6.40633C0.742207 6.32442 0.791699 6.25 0.854283 6.18741C0.916866 6.12483 0.991286 6.07534 1.0732 6.04182C1.15512 6.00831 1.24289 5.99144 1.33139 5.99221C1.41989 5.99298 1.50736 6.01137 1.58868 6.0463C1.67 6.08123 1.74355 6.13201 1.80503 6.19567L3.99995 8.39059L6.19487 6.19567C6.32058 6.07426 6.48895 6.00708 6.66371 6.00859C6.83848 6.01011 7.00565 6.08021 7.12924 6.20379C7.25282 6.32738 7.32292 6.49455 7.32444 6.66932C7.32595 6.84408 7.25877 7.01245 7.13735 7.13816L4.47119 9.80432C4.34622 9.92933 4.17671 9.99958 3.99995 9.99962Z" fill="white"></path></svg>
    </div>
    </button>
    <button class="flex items-center px-[10px] bg-[#6080ff] rounded-md h-full"><p>ВОЙТИ ЧЕРЕЗ STEAM</p>
        <img src="../public/steam.svg" class="w-[13px] ml-[7px]"/></button>
    </div>
</div>
</template>

<script setup></script>
