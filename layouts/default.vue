<template>
  <div
    class="relative min-h-screen bg-black sm:items-center sm:pt-0 text-white"
  >
    <TheHeader />
    <Nuxt />
    <TheFooter />
  </div>
</template>

<script>
export default {
  name: 'LayoutDefault',
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700;800;900&family=Poppins:wght@600&display=swap');

body {
  font-family: 'Montserrat', sans-serif !important;
}
html {
  scroll-behavior: smooth;
}

.nuxt-link-exact-active .nuxt-link-active{
  color: #FCE82F!important;
}
</style>
