<template>
    <!-- main part -->
    <div class="flex-1 border-r border-gray-100  overflow-y-auto">
          <div class="flex flex-col">
            <!-- page title -->
            <div class="border-b border-gray-100 px-4 py-3 text-xl font-bold">
              Home
            </div>
            <!-- tweeting part -->
            <div class="flex p-3 border-b border-gray-100">
              <img src="https://picsum.photos/100" class="w-10 h-10 rounded-full hover:opacity-80 cursor-pointer">
              <div class="flex flex-1 flex-col ml-2">
                <textarea class="w-full text-lg font-bold focus:outline-none resize-none" 
                          placeholder="What is happening?!"></textarea>
                <div class="text-right">
                  <button class="hover:bg-dark bg-primary text-white text-sm font-bold rounded-full px-4 py-2">Tweet</button>
                </div>
              </div>
            </div>
            <!-- tweets -->
            <div>
              <div class="flex p-3 border-b border-gray-100">
                <img src="https://picsum.photos/100" class="w-10 h-10 rounded-full hover:opacity-80 cursor-pointer">
                <div class="flex flex-1 flex-col ml-3 space-y-1">
                  <div class="font-light space-x-1">
                    <span class="font-bold">𝐀</span>
                    <span class="text-gray-500">@anoffif</span>
                    <span class="text-gray-500">·</span>
                    <span class="text-gray-500">17m</span>
                  </div>
                  <!-- tweet body -->
                  <div>벌써 월요일이야.. ..</div>
                  <!-- tweet actions -->
                  <div class="flex justify-between">
                    <div class="text-gray-500 hover:text-primary">
                      <i class="far fa-comment hover:bg-blue-50 rounded-full p-2"></i>
                      <span class="ml-2 text-sm">2</span>
                    </div>
                    <div class="text-gray-500 hover:text-green-500">
                      <i class="fas fa-retweet hover:bg-green-50 rounded-full p-2"></i>
                      <span class="ml-2 text-sm">5</span>
                    </div>
                    <div class="text-gray-500 hover:text-pink-500">
                      <i class="far fa-heart hover:bg-pink-50 rounded-full p-2"></i>
                      <span class="ml-2 text-sm">32</span>
                    </div>
                    <div class="text-gray-500 hover:text-primary">
                      <i class="far fa-share-square hover:bg-blue-50 rounded-full p-2"></i>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
    </div>
    <!-- trend part -->
    <Trends />
</template>

<script>
import Trends from '../components/Trends.vue'
export default {
  components: { Trends },
  setup() {},
}
</script>
