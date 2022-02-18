<template>
  <header class="px-4 md:px-44 flex justify-end items-center h-20 sticky top-0 z-50 md:bg-black">
    <div class="md:hidden relative right-0 top-0">
      <button
        class="z-20 fixed right-2 top-2 px-4 py-4 bg-yellow-500 md:hover:bg-yellow-200 transform duration-500 ease-in-out md:hover:scale-110 motion-reduce:transform-none text-white m-2 focus:outline-none"
        @click="menu = !menu"
      >
        <svg
          class="h-8 w-8"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            v-show="!menu"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h7"
          />
          <path
            v-show="menu"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M6 18L18 6M6 6l12 12"
          />
          https://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@github.com/chinedu16/revent-digital-fe-test.git
        </svg>
      </button>

      <ul
        v-show="menu"
        class="flex flex-col left-0 w-full h-full bg-gray-800 text-gray-400 text-center z-10 fixed sm:px-3 sm:py-2 md:px-8 md:py-4 "
        style="display: none"
        @click.prevent="menu = false"
      >
      
        <li class="text-lg py-2">
          <a href="#about-us" class="px-2 hover:text-gray-200">About Us</a>
        </li>
        <li class="text-lg py-2">
          <a href="#experience" class="px-2 hover:text-gray-200">Experience</a>
        </li>
        <li class="text-lg py-2">
          <a href="#portfolio" class="px-2 hover:text-gray-200">Portfolio</a>
        </li>
        
        <li class="text-lg py-2">
          <a href="#contact" class="px-2 hover:text-gray-200">Contact</a>
        </li>
      </ul>
    </div>
    <nav class="hidden md:block">
      <ul class="flex space-x-16">
        <li class="text-lg font-semibold">
          <nuxt-link  to="#about-us"> About Us </nuxt-link>
        </li>
        
        <li class="text-lg font-semibold">
          <nuxt-link to="#experience"> Experience </nuxt-link>
        </li>
        <li class="text-lg font-semibold">
          <nuxt-link to="#portfolio"> Portfolio </nuxt-link>
        </li>
        <li class="text-lg font-semibold">
          <nuxt-link to="#contact"> Contact </nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  data() {
    return {
      menu: false,
    }
  }
}
</script>

<style scoped>
.nuxt-link-exact-active .nuxt-link-active{
  color: #FCE82F!important;
}
</style>
