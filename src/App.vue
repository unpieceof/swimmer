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
              <div class="text-sm font-bold text-left">𝐀</div>
              <div class="text-xs text-gray-500 font-medium">@anoffif</div>
            </div>
            <i class="fa-solid fa-ellipsis-h fa-fw text-lg ml-auto hover:text-primary hidden lg:block"></i>
          </button>
        </div>
        <div class="lg:hidden mb-5 flex justify-center">
          <img src="https://picsum.photos/100" class="w-10 h-10 rounded-full cursor-pointer hover:opacity-50">
        </div>
    </div>
    <div class="flex-1">
      <div class="flex h-screen">
        <!-- main section -->
        <div class="flex-1 border-r border-gray-100">
          <div class="flex flex-col">
            <!-- page title -->
            <div class="border-b border-gray-100 px-4 py-3 text-xl font-bold">
              Home
            </div>
            <!-- tweeting section -->
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
                      <i class="far fa-retweet hover:bg-green-50 rounded-full p-2"></i>
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
            <!-- dummy tweets-->
            <div>
              <div class="flex p-3 border-b border-gray-100">
                <img src="https://picsum.photos/100" class="w-10 h-10 rounded-full hover:opacity-80 cursor-pointer">
                <div class="flex flex-1 flex-col ml-3 space-y-1">
                  <div class="font-light space-x-1">
                    <span class="font-bold">𝐀</span>
                    <span class="text-gray-500">@anoffif</span>
                    <span class="text-gray-500">·</span>
                    <span class="text-gray-500">18m</span>
                  </div>
                  <!-- tweet body -->
                  <div>이것은 테스트 트윗입니다!</div>
                  <!-- tweet actions -->
                  <div class="flex justify-between">
                    <div class="text-gray-500 hover:text-primary">
                      <i class="far fa-comment hover:bg-blue-50 rounded-full p-2"></i>
                      <span class="ml-2 text-sm"></span>
                    </div>
                    <div class="text-gray-500 hover:text-green-500">
                      <i class="far fa-retweet hover:bg-green-50 rounded-full p-2"></i>
                      <span class="ml-2 text-sm"></span>
                    </div>
                    <div class="text-gray-500 hover:text-pink-500">
                      <i class="far fa-heart hover:bg-pink-50 rounded-full p-2"></i>
                      <span class="ml-2 text-sm">3</span>
                    </div>
                    <div class="text-gray-500 hover:text-primary">
                      <i class="far fa-share-square hover:bg-blue-50 rounded-full p-2"></i>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div>
              <div class="flex p-3 border-b border-gray-100">
                <img src="https://picsum.photos/100" class="w-10 h-10 rounded-full hover:opacity-80 cursor-pointer">
                <div class="flex flex-1 flex-col ml-3 space-y-1">
                  <div class="font-light space-x-1">
                    <span class="font-bold">𝐀</span>
                    <span class="text-gray-500">@anoffif</span>
                    <span class="text-gray-500">·</span>
                    <span class="text-gray-500">20m</span>
                  </div>
                  <!-- tweet body -->
                  <div>지금은 껍데기 만드는 중 😝</div>
                  <!-- tweet actions -->
                  <div class="flex justify-between">
                    <div class="text-gray-500 hover:text-primary">
                      <i class="far fa-comment hover:bg-blue-50 rounded-full p-2"></i>
                      <span class="ml-2 text-sm">5</span>
                    </div>
                    <div class="text-gray-500 hover:text-green-500">
                      <i class="far fa-retweet hover:bg-green-50 rounded-full p-2"></i>
                      <span class="ml-2 text-sm"></span>
                    </div>
                    <div class="text-gray-500 hover:text-pink-500">
                      <i class="far fa-heart hover:bg-pink-50 rounded-full p-2"></i>
                      <span class="ml-2 text-sm">53</span>
                    </div>
                    <div class="text-gray-500 hover:text-primary">
                      <i class="far fa-share-square hover:bg-blue-50 rounded-full p-2"></i>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div>
              <div class="flex p-3 border-b border-gray-100">
                <img src="https://picsum.photos/100" class="w-10 h-10 rounded-full hover:opacity-80 cursor-pointer">
                <div class="flex flex-1 flex-col ml-3 space-y-1">
                  <div class="font-light space-x-1">
                    <span class="font-bold">𝐀</span>
                    <span class="text-gray-500">@anoffif</span>
                    <span class="text-gray-500">·</span>
                    <span class="text-gray-500">21m</span>
                  </div>
                  <!-- tweet body -->
                  <div>긴 트윗을 쓰면 어떻게 보일까? 140자 꽉 채웠을 때.. 하지만 글자수 카운터 쓰기는 귀찮으니까 대충 두 세 줄 써봐야겠다. 지금은 스타벅스에서 엄마와 각자 할 일을 하고 있어요. 일요일이 끝나가다니.. ..</div>
                  <!-- tweet actions -->
                  <div class="flex justify-between">
                    <div class="text-gray-500 hover:text-primary">
                      <i class="far fa-comment hover:bg-blue-50 rounded-full p-2"></i>
                      <span class="ml-2 text-sm">1</span>
                    </div>
                    <div class="text-gray-500 hover:text-green-500">
                      <i class="far fa-retweet hover:bg-green-50 rounded-full p-2"></i>
                      <span class="ml-2 text-sm">155</span>
                    </div>
                    <div class="text-gray-500 hover:text-pink-500">
                      <i class="far fa-heart hover:bg-pink-50 rounded-full p-2"></i>
                      <span class="ml-2 text-sm">2</span>
                    </div>
                    <div class="text-gray-500 hover:text-primary">
                      <i class="far fa-share-square hover:bg-blue-50 rounded-full p-2"></i>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div>
              <div class="flex p-3 border-b border-gray-100">
                <img src="https://picsum.photos/100" class="w-10 h-10 rounded-full hover:opacity-80 cursor-pointer">
                <div class="flex flex-1 flex-col ml-3 space-y-1">
                  <div class="font-light space-x-1">
                    <span class="font-bold">𝐀</span>
                    <span class="text-gray-500">@anoffif</span>
                    <span class="text-gray-500">·</span>
                    <span class="text-gray-500">50m</span>
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
                      <i class="far fa-retweet hover:bg-green-50 rounded-full p-2"></i>
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
                      <i class="far fa-retweet hover:bg-green-50 rounded-full p-2"></i>
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
            <!-- end of dummy-->
          </div>
        </div>
        <!-- trend section -->
        <div class="w-2/5">trend</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style></style>