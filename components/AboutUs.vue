<template>
  <div id="about-us" class="px-4 md:px-44 p-10 md:p-12">
    <div class="flex items-center justify-center">
      <section-title title="About Us" />
    </div>
    <div class="mt-12 md:flex justify-between items-center">
      <img src="~/assets/man-meeting.png" class=" md:w-3/6" />
      <div class="md:ml-12 leading-8 mt-6 md:mt-0 md:w-3/6" >
        <h5 class="text-xl font-semibold">We focus on value and excellence</h5>
        <p class="mt-6 md:text-lg">
          We are focused on providing products which deliver demonstrably good
          value for our clients and end-customers be that a specific return,
          outperforming an index or achieving returns at lower risk.
        </p>
        <p class="mt-4 md:text-lg">
          Through achieving value for the clients whose assets we manage,
          efficiently controlling costs, effectiveness and efficiency, we
          deliver value to our shareholders and wider stakeholders
        </p>
        <button-component class="mt-10" title="Work with Us" />
      </div>
    </div>
  </div>
</template>

<script>
import ButtonComponent from './ButtonComponent.vue'
import SectionTitle from './SectionTitle.vue'
export default {
  name: 'NuxtTutorial',
  components: { SectionTitle, ButtonComponent },
}
</script>

    ButtonComponent