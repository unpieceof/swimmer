<template>
  <div class="hidden lg:block lg:w-1/3 lg:mr-20 px-4 py-2">
          <!-- twitter search input -->
          <div class="relative mb-5">
            <input type="text" 
            placeholder="Search Twitter"
            class="pl-10 rounded-full w-full p-2 bg-gray-100 text-sm focus:outline-none focus:ring-1 focus:ring-primary focus:bg-white" />
            <i class="fas fa-search absolute left-0 mt-2 ml-3 text-sm text-primary"></i>
          </div>
          <!-- trend for me -->
          <div class="w-full rounded-xl bg-gray-50 flex flex-col">
            <div class="flex items-center justify-between p-3 border-b border-gray-100">
              <span class="text-lg font-bold">Trends for you</span>
              <i class="text-center fas fa-gear text-lg text-primary hover:bg-blue-50 px-2 py-1 rounded-full cursor-pointer"></i>
            </div>
            <!-- dummy trends -->
            <div class="border-b border-gray-100 hover:bg-gray-100 px-4 py-2 cursor-pointer">
              <div class="flex">
                <div class="flex-1 flex flex-col">
                  <div class="text-gray-500 text-sm">Trending in South Korea</div>
                  <div class="font-bold">개교기념일</div>
                  <div class="text-gray-500 text-sm">2,016 Tweets</div>
                </div>
                <i class="fas fa-ellipsis-h text-gray-500 hover:text-primary"></i>
              </div>
            </div>
            <!-- dummy end -->
            <div class="p-4 hover:bg-gray-100 rounded-xl  cursor-pointer">
              <span class="text-primary">Show more</span>
            </div>
          </div>
          <!-- follow recommend -->
          <div class="w-full rounded-xl bg-gray-50 flex flex-col mt-5">
            <div class="p-3 border-b border-gray-100">
              <span class="text-lg font-bold">Who to follow</span>
            </div>
            <!-- dummy user -->
            <div class="border-b border-gray-100 hover:bg-gray-100 px-4 py-2">
              <div class="flex items-center">
                <img src="https://picsum.photos/200" class="w-10 h-10 rounded-full mr-2">
                <div class="flex-1 flex flex-col">
                  <div class="font-bold cursor-pointer hover:underline">앙뇽</div>
                  <div class="text-gray-500 text-sm">@hi_friend</div>
                </div>
                <div>
                  <button class="bg-black text-white text-sm font-bold hover:bg-dark px-4 py-1.5 rounded-full">Follow</button>
                </div>
              </div>
            </div>
            <!-- dummy end -->
            <div class="p-4 hover:bg-gray-100 rounded-xl cursor-pointer">
              <span class="text-primary">Show more</span>
            </div>
          </div>
        </div>
</template>

