<script setup lang="ts">
  import { useLifecycleLogger } from "@/common/hooks/lifecycleLogger";

  const name = "Page six";
  useLifecycleLogger({ name });
</script>

<template>
  <div class="page">
    {{ name }}
  </div>
</template>

<style scoped></style>
