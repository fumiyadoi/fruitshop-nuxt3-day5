<template>
  <div class="md:h-[240px] h-[120px] w-full bg-white flex">
    <img
      src="@/assets/images/apple.png"
      class="object-cover h-full"
      alt="apple"
    />
    <div class="w-full flex flex-col justify-between m-6">
      <div class="flex justify-between items-center">
        <div class="text-lg">リンゴ</div>
        <div class="text-xl font-bold text-red-500">¥200</div>
      </div>
      <div class="flex justify-between items-center">
        <div class="flex items-center gap-4">
          <div class="whitespace-nowrap">数量</div>
          <Select />
        </div>
        <Button text="削除する" />
      </div>
    </div>
  </div>
</template>
