<template>
  <div class="flex h-screen">
    <!-- side section -->
    <div class="w-1/5 mt-4 ml-10 flex flex-col justify-between">
      <div>
        <!-- twitter logo -->
        <i class="fa-solid fa-water-ladder text-4xl text-primary ml-3"></i>
        <!-- sidemenu icons -->
        <div class="flex flex-col items-start space-y-3">
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-solid fa-house-chimney fa-fw text-2xl"></i>
            <span class="ml-4 text-xl">Home</span>
          </div>
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-solid fa-hashtag fa-fw text-2xl"></i>
            <span class="ml-4 text-xl">Explore</span>
          </div>
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-regular fa-bell fa-fw text-2xl"></i>
            <span class="ml-4 text-xl">Notifications</span>
          </div>
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-regular fa-envelope fa-fw text-2xl"></i>
            <span class="ml-4 text-xl">Messages</span>
          </div>
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-solid fa-list fa-fw text-2xl"></i>
            <span class="ml-4 text-xl">Lists</span>
          </div>
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-regular fa-bookmark fa-fw text-2xl"></i>
            <span class="ml-4 text-xl">Bookmarks</span>
          </div>
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-regular fa-user fa-fw text-2xl"></i>
            <span class="ml-4 text-xl">Profile</span>
          </div>
          <div class="hover:text-primary hover:bg-blue-50 px-4 py-1 rounded-full mt-5">
            <i class="fa-solid fa-ellipsis-h fa-fw text-2xl"></i>
            <span class="ml-4 text-xl">More</span>
          </div>
        </div>
        <!-- tweet button -->
        <div class="mr-10">
          <button class="mt-5 bg-primary text-white w-full h-14 rounded-full font-bold hover:bg-dark">Tweet</button>
        </div>
      </div>
        <!-- profile button -->
        <div class="mr-10 mb-5">
          <button class="mt-5 px-2 py-2 w-full h-14 rounded-full font-bold hover:bg-gray-100 flex items-center">
            <img src="https://picsum.photos/100" class="w-10 h-10 rounded-full">
            <div class="ml-4">
              <div class="text-sm font-bold text-left">A</div>
              <div class="text-xs text-gray-500 font-medium">@anoffif</div>
            </div>
            <i class="fa-solid fa-ellipsis-h fa-fw text-lg ml-auto "></i>
          </button>
        </div>
    </div>
    <div class="flex-1 bg-gray-50">home</div>
  </div>
</template>

<script>
export default {}
</script>

<style></style>