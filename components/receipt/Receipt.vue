<template>
  <div class="w-full bg-white">
    <div class="flex gap-3 ml-6 my-4">
      <div class="">
        <div class="mb-2">注文日</div>
        <div class="">2023年1月1日</div>
      </div>
      <div class="">
        <div class="mb-2">合計</div>
        <div class="">¥200</div>
      </div>
    </div>
    <hr />
    <div class="ml-8 my-6 flex flex-col gap-4">
      <div class="flex gap-4 md:h-[160px] h-[120px]">
        <img
          src="@/assets/images/apple.png"
          class="object-cover h-full"
          alt="item-image"
        />
        <div class="flex flex-col gap-3 mt-4">
          <div class="text-lg font-bold">リンゴ</div>
          <div class="">金額：¥200</div>
          <div class="">個数：1</div>
        </div>
      </div>
    </div>
  </div>
</template>
