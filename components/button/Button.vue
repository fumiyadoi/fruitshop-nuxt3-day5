<template>
  <button
    class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-3 rounded whitespace-nowrap"
  >
    {{ text }}
  </button>
</template>

<script setup lang="ts">
interface Props {
  text: string;
}

const Props = defineProps<Props>();
</script>
