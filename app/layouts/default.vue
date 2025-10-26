<template>

    <header class="h-[70px] bg-[#E4E4E4] flex items-center">
        <div class="w-[60px] h-[60px] ml-[16px] bg-[#C4C4C4] rounded-full"></div>
        <div class="ml-auto h-[70px] flex">
            <NuxtLink to="/" class="px-7 py-7 h-[70px] bg-[#D5D5D5] flex items-center">
                Home                        
            </NuxtLink>   
            <NuxtLink to="/about" class="px-7 py-7 h-[70px] hover:bg-[#DBDBDB] flex items-center">
                Options                        
            </NuxtLink>
            <NuxtLink to="/news" class="px-7 py-7 h-[70px] hover:bg-[#DBDBDB] flex items-center">
                Contact Us                        
            </NuxtLink>
        </div>
    </header>

  <main>
    <slot />
  </main>

  <footer class="h-[70px] bg-[#E4E4E4] flex items-center">
    <div class="w-[60px] h-[60px] bg-[#C4C4C4] rounded-full ml-[21px]"></div>
    <div class="w-[60px] h-[60px] bg-[#C4C4C4] rounded-full ml-[21px]"></div>
    <div class="w-[60px] h-[60px] bg-[#C4C4C4] rounded-full ml-[21px]"></div>
    <div class="ml-auto">
      <h1 class="ml-[71px] w-[608px] text-[24px] font-bold">@ 2022  Ar Filters Majito - Maria José Mercau</h1>
    </div>
  </footer>

</template>