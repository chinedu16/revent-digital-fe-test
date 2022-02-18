<template>
  <div id="contact" class="px-4 md:px-44 p-10 md:pt-12 pb-36">
    <div class="flex items-center justify-center">
      <section-title title="Get in Touch" />
    </div>
    <div class="mt-12 md:flex justify-center items-center">
      <div class="flex justify-center items-center">
        <div class="flex flex-col items-center">
          <img src="~/assets/call.svg" class="mb-3" />
          <h3 class="text-lg md:text-2xl font-bold">Call Us</h3>
          <h5 class="font-extralight text-base md:text-lg mt-3">
            +234-806 749-700
          </h5>
        </div>
        <div class="ml-10 md:ml-80 flex flex-col items-center">
          <img src="~/assets/send.svg" class="mb-3" />
          <h3 class="text-lg md:text-2xl font-bold">Send Email</h3>
          <h5 class="font-extralight text-base md:text-lg mt-3">
            revent@digital.com
          </h5>
        </div>
      </div>
    </div>
    <div class="mt-7">
      <div class="grid grid-cols-2 gap-4">
        <input
          type="text"
          placeholder="Company Name"
          class="w-full text-black font-semibold border border-gray-300 p-2 my-2 rounded-md focus:outline-none focus:ring-2 ring-blue-200"
        />
        <input
          type="text"
          placeholder="Phone Number"
          class="w-full text-black font-semibold border border-gray-300 p-2 my-2 rounded-md focus:outline-none focus:ring-2 ring-blue-200"
        />
      </div>
      <input
        type="text"
        placeholder="Company Email"
        class="w-full mt-7 text-black font-semibold border border-gray-300 p-2 my-2 rounded-md focus:outline-none focus:ring-2 ring-blue-200"
      />
      <textarea
        id=""
        name=""
        placeholder="Message"
        cols="30"
        rows="10"
        class="w-full mt-7 text-black font-semibold border border-gray-300 p-2 my-2 rounded-md focus:outline-none focus:ring-2 ring-blue-200"
      ></textarea>
      <ButtonComponent class="mt-7" title="Send message" />
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
