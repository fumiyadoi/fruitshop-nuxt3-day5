<template>
  <div class="text-sm mb-3">
    {{ label }}
  </div>
  <div class="mb-3">
    <Input />
  </div>
</template>

<script setup lang="ts">
interface Props {
  label: string;
}

const Props = defineProps<Props>();
</script>
