<template>
  <div class="flex-1 flex">
    <!-- chat list -->
    <div class="w-2/5 border-r border-gray-200 overflow-y-scroll">
        <div class="flex flex-col">
            <div class="p-3 font-bold text-xl border-b border-gray-200">Messages</div>
            <div class="flex px-3 py-4 hover:bg-gray-50 border-b border-gray-200 bg-gray-200">
                <img 
                    src="http://picsum.photos/200"
                    class="w-10 h-10 rounded-full cursor-pointer mr-2"
                />
                <div>
                    <div class="flex space-x-1">
                        <div class="font-bold">앙뇽</div>
                        <div class="text-gray-500">@hi_friend</div>
                        <div class="text-gray-500">Mar 30</div>
                    </div>
                    <div>메세지</div>
                </div>
            </div>
            <!-- a chat list -->
            <div class="flex px-3 py-4 hover:bg-gray-50 border-b border-gray-200" 
                v-for="message in 5" 
                :key="message"
            >
                <img 
                    src="http://picsum.photos/200"
                    class="w-10 h-10 rounded-full cursor-pointer mr-2"
                />
                <div>
                    <div class="flex space-x-1">
                        <div class="font-bold">앙뇽</div>
                        <div class="text-gray-500">@hi_friend</div>
                        <div class="text-gray-500">Mar 30</div>
                    </div>
                    <div>메세지</div>
                </div>
            </div>
        </div>
    </div>
    <!-- chatting -->
    <div class="w-3/5 border-r border-gray-200"></div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>