<template>
  <div class="px-4 md:px-44 pb-12 pb-16">
    <div class="flex-col md:flex-row flex justify-between items-center">
      <div class="leading-8 md:w-3/6">
        <nuxt-link to="/" class="">
          <img src="~/assets/logo.svg" class="mb-16" />
        </nuxt-link>
        <div class="leading-8">
          <h5 class="text-3xl md:text-4xl font-semibold md:w-3/5 mt-10 md:mt-0">
            Innovative Solution Taliored to your Business need
          </h5>
          <p class="mt-6 md:text-lg">
            We can partner with your business to provide a symbiotic
            relationship and synergy to help you or your business achieve more
            business growth through strategic financial advisory, investment
            business and human resource planning and management.
          </p>

          <button-component class="mt-10" title="Get in touch" />
          <div class="flex mt-8 space-x-4">
            <img src="~/assets/behance.svg" />
            <img src="~/assets/dribble.svg" />
            <img src="~/assets/facebook.svg" />
          </div>
        </div>
      </div>
      <div class="md:w-3/6 relative flex justify-end mt-10 md:mt-0">
        <img class="absolute" src="~/assets/rectangle.svg" />
        <img src="~/assets/yellow-ball.svg" />
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped></style>
