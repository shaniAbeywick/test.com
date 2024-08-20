<template>
  <div class="sm:container px-4 pt-20">
    <h2 class="uppercase text-black-100 text-4xl text-center">Services</h2>
    <h3 class="text-black-50 text-xl pt-1 text-center uppercase tracking-widest">Dine & Relax</h3>
    <div class="grid lg:grid-cols-2 grid-cols-1 pt-10 lg:gap-y-12 gap-y-0">
        <div class="bg-gray-50 bg-opacity-20 p-10">
            <h3 class="text-xl text-black-50 uppercase tracking-widest">Dining</h3>
            <h2 class="text-black-100 text-4xl pt-2">Restaurant</h2>
            <p class="text-base text-black-50 pt-2">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et, deserunt accusamus ratione soluta fugiat ducimus quis vel repellat quae autem nihil rerum enim perspiciatis deleniti perferendis labore distinctio, vitae a.</p>
            <a href="./services"><button type="button" class="mt-8 buttontext text-white bg-red-100 hover:bg-red-100 focus:ring-none font-medium rounded-sm text-base px-8 py-2.5 me-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">EXPLORE</button></a>
        </div>
        <div> <img src="/img/service1.jpg" alt="RestaurantImg" class="bg-cover h-full" /></div>
        <div class="mt-8 lg:mt-0"> <img src="/img/service3.jpg" alt="CelebrateImg" class="bg-cover h-full" /></div>
        <div class="bg-gray-50 bg-opacity-20 p-10">
            <h3 class="text-xl text-black-50 uppercase tracking-widest">Celebrate</h3>
            <h2 class="text-black-100 text-4xl pt-2">banquet Hall</h2>
            <p class="text-base text-black-50 pt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut molestiae similique animi. Blanditiis ratione neque nesciunt et molestias quam eaque, illum maxime tempore temporibus cumque, veniam dolorum odit minima consectetur.</p>
            <a href="./services"><button type="button" class="mt-8 buttontext text-white bg-red-100 hover:bg-red-100 focus:ring-none font-medium rounded-sm text-base px-8 py-2.5 me-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">EXPLORE</button></a>
        </div>
        <div class="bg-gray-50 bg-opacity-20 p-10 mt-8 lg:mt-0">
            <h3 class="text-xl text-black-50 uppercase tracking-widest">Playtime</h3>
            <h2 class="text-black-100 text-4xl pt-2">Sports & Games</h2>
            <p class="text-base text-black-50 pt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum et eius illo doloremque blanditiis. Mollitia, modi? Natus possimus repudiandae, quisquam dolorum similique sit dolorem quo ipsum beatae distinctio, placeat consequuntur!</p>
            <a href="./services"><button type="button" class="mt-8 buttontext text-white bg-red-100 hover:bg-red-100 focus:ring-none font-medium rounded-sm text-base px-8 py-2.5 me-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">EXPLORE</button></a>
        </div>
        <div> <img src="/img/service2.jpg" alt="PlaytimeImg" class="bg-cover h-full" /></div>

    </div>  
  </div>
  <div class="mt-20"><img src="/img/footer.jpg" alt="PlaytimeImg" class="object-cover h-[500px] w-full" /></div> 
</template>

<script setup>
</script>

<style scoped>
h2 {
  font-family: "Philosopher", sans-serif;
}
h3 ,.buttontext,p {
  font-family: "Barlow", sans-serif;
}
</style>