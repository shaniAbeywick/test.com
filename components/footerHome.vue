<template>
  <div class="bg-gradient-to-r from-neutral-700 via-neutral-800 to-gray-600">
    <div class="sm:container px-4 pt-20">
      <a href="/home">
        <img
          src="/img/logo.png"
          alt="logoImg"
          class="w-auto h-16 md:h-28 mx-auto"
        />
      </a>
      <p
        class="lg:text-base text-sm text-white font-thin text-center pt-8 max-w-[100ch] mx-auto"
      >
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Qui exercitationem eaque consectetur tempora ut cupiditate! Minima dolore illo, excepturi repellat nulla corrupti sapiente! Quia odit esse vel quibusdam. Laborum, voluptatem?
      </p>
      <div class="flex justify-center items-center">
        <a
          href="/contact"
          class="mt-8 buttontext uppercase text-white bg-white hover:bg-neutral-400 bg-opacity-15 focus:ring-none font-medium rounded-sm lg:text-base text-sm px-8 py-2.5 me-2 mb-2 border border-white dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
        >
          Contact Us
        </a>
      </div>
      <hr class="border-gray-100 border-opacity-20 my-8" />
      <div
        class="grid lg:grid-cols-4 grid-cols-2 gap-x-4 lg:gap-y-0 gap-y-16 items-start"
      >
        <div class="flex flex-col justify-center items-center">
          <h2 class="text-white lg:text-4xl text-xl">Stay</h2>
          <h3 class="text-black-50 uppercase text-sm mt-3">Stay with us</h3>
          <h3 class="text-black-50 uppercase text-sm mt-1">Explore rooms</h3>
          <h3 class="text-black-50 uppercase text-sm mt-1">enjoy amenities</h3>
        </div>
        <div class="flex flex-col justify-center items-center">
          <h2 class="text-white lg:text-4xl text-xl">Dine</h2>
          <h3 class="text-black-50 uppercase text-sm mt-3">dine with us</h3>
          <h3 class="text-black-50 uppercase text-sm mt-1">enjoy a meal</h3>
          <h3 class="text-black-50 uppercase text-sm mt-1">have a drink</h3>
        </div>
        <div class="flex flex-col justify-center items-center">
          <h2 class="text-white lg:text-4xl text-xl">More</h2>
          <!-- Link to "terms & conditions" -->
          <a
            href="/#"
            class="text-black-50 uppercase text-sm mt-3 block hover:text-blue-500"
            >Terms And Conditions</a
          >
          <!-- Link to "privacy Policy" -->
          <a
            href="/#"
            class="text-black-50 uppercase text-sm mt-1 block hover:text-blue-500"
            >Privacy Policy</a
          >
          <!-- Link to "Cookies Policy" -->
          <a
            href="/#"
            class="text-black-50 uppercase text-sm mt-1 block hover:text-blue-500"
            >Cookies Policy</a
          >
          <!-- Link to "Safety and security" -->
          <a
            href="/#"
            class="text-black-50 uppercase text-sm mt-1 block hover:text-blue-500"
            >Safety and security</a
          >
          <!-- Link to "FAQ" -->
          <a
            href="/#"
            class="text-black-50 uppercase text-sm mt-1 block hover:text-blue-500"
            >FAQ</a
          >
        </div>
        <div class="flex flex-col justify-center items-center">
          <h2 class="text-white lg:text-4xl text-xl">Follow</h2>
          <nuxt-link
            to="#"
            class="text-black-50 uppercase text-sm mt-3 hover:text-blue-500"
            >Facebook</nuxt-link
          >
          <!-- <nuxt-link to="https://twitter.com" class="text-black-50 uppercase text-sm mt-1 hover:text-blue-500">Twitter</nuxt-link> -->
          <nuxt-link
            to="#"
            class="text-black-50 uppercase text-sm mt-1 hover:text-blue-500"
            >Instagram</nuxt-link
          >
        </div>
      </div>
      <hr class="border-gray-100 border-opacity-20 lg:mt-32 mt-10" />
      <div class="flex lg:flex-row flex-col lg:justify-between py-4">
        <h3 class="text-white text-sm">
          © test.com 2024. All rights reserved.
        </h3>
        <h3 class="text-white text-sm mt-2 lg:mt-0">
          Design & Developed by <a href="#">By shani</a>
        </h3>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>

<style scoped>
h2 {
  font-family: "Philosopher", sans-serif;
}
h3,
a,
.buttontext,
p {
  font-family: "Barlow", sans-serif;
}
</style>