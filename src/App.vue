<template>
  <div class="flex h-screen">
    <!-- side section -->
    <div class="w-1/5 mt-4 lg:ml-10 flex flex-col justify-between border-r border-gray-200">
      <div class="flex flex-col items-center lg:items-start">
        <!-- twitter logo -->
        <i class="fa-solid fa-water-ladder text-4xl text-primary lg:ml-3"></i>
        <!-- sidemenu icons -->
        <div class="flex flex-col items-start space-y-3">
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-solid fa-house-chimney fa-fw text-2xl"></i>
            <span class="ml-4 text-xl hidden lg:inline-block">Home</span>
          </div>
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-solid fa-hashtag fa-fw text-2xl"></i>
            <span class="ml-4 text-xl hidden lg:inline-block">Explore</span>
          </div>
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-regular fa-bell fa-fw text-2xl"></i>
            <span class="ml-4 text-xl hidden lg:inline-block">Notifications</span>
          </div>
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-regular fa-envelope fa-fw text-2xl"></i>
            <span class="ml-4 text-xl hidden lg:inline-block">Messages</span>
          </div>
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-regular fa-user fa-fw text-2xl"></i>
            <span class="ml-4 text-xl hidden lg:inline-block">Profile</span>
          </div>
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-solid fa-ellipsis-h fa-fw text-2xl"></i>
            <span class="ml-4 text-xl hidden lg:inline-block">More</span>
          </div>
        </div>
        <!-- tweet button -->
        <div class="w-full lg:pr-10 flex justify-center">
          <button class="mt-5 bg-primary text-white lg:w-full w-14 h-14 rounded-full font-bold hover:bg-dark">
            <span class="hidden lg:block">Tweet</span>
            <i class="fas fa-plus lg:hidden"></i>
          </button>
        </div>
      </div>
        <!-- profile button -->
        <div class="mr-5 mb-5">
          <button class="hidden lg:flex mt-5 px-2 py-2 w-full h-14 rounded-full font-bold hover:bg-gray-100 flex items-center">
            <img src="https://picsum.photos/100" class="w-10 h-10 rounded-full">
            <div class="lg:ml-4 hidden lg:block">
              <div class="text-sm font-bold text-left">A</div>
              <div class="text-xs text-gray-500 font-medium">@anoffif</div>
            </div>
            <i class="fa-solid fa-ellipsis-h fa-fw text-lg ml-auto hover:text-primary hidden lg:block"></i>
          </button>
        </div>
        <div class="lg:hidden mb-5 flex justify-center">
          <img src="https://picsum.photos/100" class="w-10 h-10 rounded-full cursor-pointer hover:opacity-50">
        </div>
    </div>
    <div class="flex-1">home</div>
  </div>
</template>

<script>
export default {}
</script>

<style></style>