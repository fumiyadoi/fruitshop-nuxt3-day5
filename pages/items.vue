<template>
  <NuxtLayout>
    <div class="w-full flex flex-col items-center pb-8">
      <div class="max-w-[768px] px-3">
        <div class="w-full flex justify-between my-4">
          <div class="w-full mr-4">
            <Input />
          </div>
          <Button text="検索する" />
        </div>
        <div class="grid md:grid-cols-3 grid-cols-2 gap-4">
          <ItemCard />
          <ItemCard />
          <ItemCard />
          <ItemCard />
          <ItemCard />
          <ItemCard />
        </div>
      </div>
    </div>
  </NuxtLayout>
</template>
