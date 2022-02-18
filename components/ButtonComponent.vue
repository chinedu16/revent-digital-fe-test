<template>
  <div>
    <button
      class="py-3 md:py-4 px-6 md:px-12 btn-bg text-lg text-black font-bold transition duration-300 ease-in-out bg-regal-yellow hover:bg-yellow-400"
    >
      {{ title }}
    </button>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      default: '',
      type: String,
    },
  },
}
</script>

<style scoped>
.btn-bg {
  border-radius: 10px;
  font-family: 'Poppins', sans-serif;
}
</style>
