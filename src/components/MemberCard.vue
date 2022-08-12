<script setup lang="ts">

</script>

<template>
  <div class="py-2.5 mb-2.5 flex flex-col items-center border border-gray-300 bg-white">
        <div class=" font-Lobster text-5xl my-8">Instagram</div>
        <div class="mb-2">
            <form class=" flex flex-col items-center" id="loginForm" method="post">
                <input type="text" name="account" placeholder="用戶名稱" class=" h-8 w-64 mb-2 bg-white rounded p-2 text-gray-600 text-sm flex items-center font-light border border-gray-300"/>
                <input type="text" name="password" placeholder="密碼" class=" h-8 w-64 mb-2 bg-white rounded p-2 text-gray-600 text-sm flex items-center font-light border border-gray-300"/>
                <button class=" my-2 mx-10 w-64 bg-[#0095f6] text-white py-1 rounded font-semibold">登入</button>
                <div class=" flex mt-2.5 mx-10 mb-4 w-64 items-center">
                    <div class=" w-full h-0.5 bg-[#DBDBDB]"></div>
                    <div class=" text-[#8E8E8E] mx-5">或</div>
                    <div class=" w-full h-0.5 bg-[#DBDBDB]"></div>
                </div>
                <div class=" mt-3 text-[#00376B] text-xs">忘記密碼?</div>
            </form>
        </div>
    </div>
</template>