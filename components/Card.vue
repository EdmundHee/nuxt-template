<template>
  <div
    class="w-full py-2 px-6 bg-gray-800 font-poppins shadow-xl cursor-pointer transition-all duration-500 ease-in-out hover:shadow-2xl"
  >
    <div class="w-12 h-12 rounded-full">
      <!-- TODO: Company Logo -->
      <slot name="company-logo"></slot>
    </div>
    <!-- TODO: Company Name -->
    <div class="text-lg md:text-xl font-semibold text-gray-200 tracking-wide">
      <slot name="company-name"></slot>
    </div>
    <!-- TODO: Job Descriptions -->
    <div
      class="text-gray-600 text-sm md:text-base text-justify font-thin leading-none my-2"
    >
      <slot name="job-details"></slot>
    </div>
    <!-- TODO: Job Title -->
    <div class="text-xs text-gray-500">
      <slot name="job-title"></slot>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>