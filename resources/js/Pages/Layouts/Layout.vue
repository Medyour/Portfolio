<template>
<nav class="bg-transparent absolute top-0 left-0 right-0 z-30 lg:flex lg:flex-row lg:flex-nowrap lg:justify-start flex items-center py-2 px-4">
    <div class="w-full mx-auto px-4 flex items-center justify-between flex-wrap lg:flex-nowrap
  max-w-[100%] sm:max-w-[540px] md:max-w-[720px] lg:max-w-[960px] xl:max-w-[1140px]">
        <a href="#" class="text-white py-[11.2px] px-0 font-black text-[24px] uppercase inline-block mr-4 whitespace-nowrap transition-all duration-300 no-underline bg-transparent">
        MedMk
        </a>
        <button class="block lg:hidden text-white/50 bg-transparent border-0 text-[16px] tracking-widest uppercase p-[4px_12px] rounded cursor-pointer leading-none">
            <span class="oi oi-menu relative inline-block align-top top-[1px] leading-none font-normal not-italic"></span> Menu
        </button>
        <div class="hidden lg:flex flex-grow items-center" id="ftco-nav">
            <ul class="flex flex-wrap flex-col lg:flex-row list-none p-0 m-0 ml-auto">
                <li>
                    <a href="#home-section" class="block text-[16px] py-[0.7rem] px-5 font-normal text-[#ffbd39] no-underline">
                        <span class="relative block pb-[2px]">Home</span>
                    </a>
                 </li>
                 <li>
                    <a href="#home-section" class="block text-[16px] py-[0.7rem] px-5 font-normal opacity-100 no-underline transition-colors duration-300 text-white hover:text-[#ffbd39]">
                        <span class="relative block pb-[2px]">About</span>
                    </a>
                 </li>
                 <li>
                    <a href="#home-section" class="block text-[16px] py-[0.7rem] px-5 font-normal opacity-100 no-underline transition-colors duration-300 text-white hover:text-[#ffbd39]">
                        <span class="relative block pb-[2px]">Resume</span>
                    </a>
                 </li>
                 <li>
                    <a href="#home-section" class="block text-[16px] py-[0.7rem] px-5 font-normal opacity-100 no-underline transition-colors duration-300 text-white hover:text-[#ffbd39]">
                        <span class="relative block pb-[2px]">Services</span>
                    </a>
                 </li>
                 <li>
                    <a href="#home-section" class="block text-[16px] py-[0.7rem] px-5 font-normal opacity-100 no-underline transition-colors duration-300 text-white hover:text-[#ffbd39]">
                        <span class="relative block pb-[2px]">Skills</span>
                    </a>
                 </li>
                 <li>
                    <a href="#home-section" class="block text-[16px] py-[0.7rem] px-5 font-normal opacity-100 no-underline transition-colors duration-300 text-white hover:text-[#ffbd39]">
                        <span class="relative block pb-[2px]">Projects</span>
                    </a>
                 </li>
                 <li>
                    <a href="#home-section" class="block text-[16px] py-[0.7rem] px-5 font-normal opacity-100 no-underline transition-colors duration-300 text-white hover:text-[#ffbd39]">
                        <span class="relative block pb-[2px]">My Blog</span>
                    </a>
                 </li>
                 <li>
                    <a href="#home-section" class="block text-[16px] py-[0.7rem] px-5 font-normal opacity-100 no-underline transition-colors duration-300 text-white hover:text-[#ffbd39]">
                        <span class="relative block pb-[2px]">Contact</span>
                    </a>
                 </li>
            </ul>
        </div>
    </div>

</nav>









<slot />
</template>
