<template>
  <div class="flex bg-[#11141c] min-h-screen text-white">
    <div class="flex flex-col w-[84px]">
      <NavTabs></NavTabs>
    </div>
    <div class="h-[60px] px-[30px] w-full">
      <Header></Header>
      <slot />
    </div>
  </div>
</template>
