<template>
  <div>
    <h1>Page id is {{ id }}</h1>
  </div>
</template>

<script setup>
  const {id} = useRoute().params
</script>