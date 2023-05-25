<template>
  <NuxtLayout>
    <div class="relative">
      <div class="flex flex-col items-center pt-6 pb-20">
        <div class="md:w-[768px] w-full flex flex-col gap-4 px-3">
          <CartItemCard />
          <CartItemCard />
          <CartItemCard />
        </div>
      </div>
      <div class="bottom-0 left-0 right-0 fixed">
        <Footer />
      </div>
    </div>
  </NuxtLayout>
</template>
