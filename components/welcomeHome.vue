<template>
    <div class="relative">
        <!-- Overlay -->
    <div class="absolute inset-0 bg-black-200 opacity-20 z-20"></div>
        <img
        src="/img/welcomeImg.jpg"
        alt="backgroundImg"
        class="object-cover w-full min-h-screen"
      />
      <div class="sm:container px-4 top-5 absolute lg:pt-20 pt-2">
         <div class="lg:flex lg:flex-row justify-between grid-cols-2">
            <div>
               <h3 class="uppercase text-white md:text-xl text-base">Welcome</h3>
               <h2 class="text-white md:text-5xl text-3xl mt-4">Lorem Ipsume dolor</h2>
               <p class="max-w-[80ch] md:text-base text-sm text-white mt-2">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corporis odit molestias, vel corrupti atque sit porro eaque, autem fugit, laboriosam libero nemo quam dolorem voluptates? Recusandae eaque est eius illo?</p>
               
            </div>
            <div class="mt-10">
                <h3 class="uppercase text-black-200 md:text-xl text-sm">Reservation</h3>
                <h3 class="uppercase text-black-200 md:text-xl text-sm mt-2">+(94) 71 00 0000</h3>
            </div>

         </div>
      </div>

    </div>
</template>

<script setup>

</script>

<style scoped>
h2{
    font-family: "Philosopher", sans-serif;;
}
h3,h4,h5,p{
    font-family: "Barlow", sans-serif;
}
</style>