<template>
    <div class="flex-1 flex flex-col border-r border-gray-100 overflow-y-auto">
        <!-- page title -->
        <div class="px-4 py-3 text-xl font-bold border-b border-gray-100">
            Notifications
        </div>
        <!-- Notifications -->
        <div class="flex flex-col hover:bg-gray-50 p-3 space-y-2 border-b border-gray-100 cursor-pointer">
            <div class="flex justify-between">
                <img src="https://picsum.photos/300" class="w-10 h-10 rounded-full hover:opacity-80">
                <i class="fas fa-ellipsis-h text-gray-500 hover:bg-blue-50 hover:text-primary rounded-full p-2 w-10 h-10 flex items-center justify-center"></i>
            </div>
            <div><span class="font-bold">요즘AI <i class="fa-solid fa-square-check text-primary"></i></span> liked your Tweet</div>
            <div class="text-gray-500">마침내~</div>
        </div>
        <div class="flex p-3 border-b border-gray-100 justify-between">
                <img src="https://picsum.photos/400" class="w-10 h-10 rounded-full hover:opacity-80 cursor-pointer">
                <div class="flex flex-1 flex-col ml-3 space-y-1">
                    <div class="font-light space-x-1">
                        <span class="font-bold">진짜친구</span>
                        <span class="text-gray-500">@realme</span>
                        <span class="text-gray-500">·</span>
                        <span class="text-gray-500">1m</span>
                    </div>
                  <!-- tweet body -->
                  <div>우리는 친구 칭긔!!!</div>
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
                <i class="fas fa-ellipsis-h text-gray-500 hover:bg-blue-50 hover:text-primary rounded-full p-2 w-10 h-10 flex items-center justify-center"></i>
              </div>
    </div>
</template>

<script>
export default {
}
</script>
