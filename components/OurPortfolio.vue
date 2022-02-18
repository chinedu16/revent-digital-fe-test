<template>
  <div id="portfolio" class="px-4 md:px-44 p-10 md:p-12">
    <div class="flex items-center justify-center">
      <section-title title="Portfolio" />
    </div>
    <div class="mt-12 md:flex justify-center items-center">
      <div class="grid grid-cols-2 gap-4 md:flex md:space-x-6">
        <div
          :class="`${
            isActive === 'all' ? 'bg-white text-black' : 'text-white'
          }`"
          class="cursor-pointer font-normal rounded-lg text-center text-xl px-4 py-3 transition duration-300 ease-in-out hover:bg-white hover:text-black"
          @click="isActive = 'all'"
        >
          All
        </div>
        <div
          :class="`${
            isActive === 'website' ? 'bg-white text-black' : 'text-white'
          }`"
          class="cursor-pointer rounded-lg font-normal text-center text-xl px-4 py-3 transition duration-300 ease-in-out hover:bg-white hover:text-black"
          @click="isActive = 'website'"
        >
          Website
        </div>
        <div
          :class="`${
            isActive === 'mobile' ? 'bg-white text-black' : 'text-white'
          }`"
          class="cursor-pointer rounded-lg font-normal text-center text-xl px-4 py-3 transition duration-300 ease-in-out hover:bg-white hover:text-black"
          @click="isActive = 'mobile'"
        >
          MobileApp
        </div>
        <div
          :class="`${
            isActive === 'css' ? 'bg-white text-black' : 'text-white'
          }`"
          class="cursor-pointer rounded-lg font-normal text-center text-xl px-4 py-3 transition duration-300 ease-in-out hover:bg-white hover:text-black"
          @click="isActive = 'css'"
        >
          CSS
        </div>
        <div
          :class="`${
            isActive === 'github' ? 'bg-white text-black' : 'text-white'
          }`"
          class="cursor-pointer rounded-lg font-normal text-center text-xl px-4 py-3 transition duration-300 ease-in-out hover:bg-white hover:text-black"
          @click="isActive = 'github'"
        >
          GitHub
        </div>
      </div>
    </div>
    <div class="grid md:grid-cols-3 gap-3 mt-10">
      <img src="~/assets/portfolio-image.png" class="w-full"/>
      <img src="~/assets/portfolio-image.png" class="w-full"/>
      <img src="~/assets/portfolio-image.png" class="w-full"/>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isActive: 'all',
    }
  },
}
</script>

<style scoped></style>
