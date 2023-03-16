<template>
  <li class="items-center">
    <a class="text-slate-700 hover:text-slate-500 text-xs uppercase py-3 font-bold block" :href="route">
      <slot/>
    </a>
  </li>
</template>

<script setup>
defineProps(['route'])
</script>

<style scoped>

</style>
