<script setup>
  import { Link } from '@inertiajs/inertia-vue3';
  
  defineProps({
    id : String
  })

</script>

<template>
  あなたはナンバー{{ id }}です。
</template>