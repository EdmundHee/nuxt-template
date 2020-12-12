<template>
  <div class="h-screen w-screen">
    <img
      src="https://images.pexels.com/photos/34600/pexels-photo.jpg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
      alt="Background Image for Landing Page"
      class="h-full w-full object-cover"
    />
    <div class="absolute bottom-0 z-10 w-screen">
      <!-- FOUNDATION : Prepare the space -->
      <div class="grid grid-cols-2 p-2">
        <div class="flex flex-col w-2/3">
          <span
            class="text-white text-7xl px-4 font-bold leading-none tracking-wide"
            >FULL STACK DEVELOPER</span
          >
          <div class="flex ml-4 pt-4 pb-10 items-center">
            <div class="border-b border-red-600 w-10 h-0.5 mx-4"></div>
            <span class="font-semibold text-lg text-red-600"
              >CHECK OUT MY PORTFOLIO</span
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
