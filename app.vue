<script setup>
const config = useAppConfig()
</script>
<template>
  <div>
      <h1>{{ config.title }}</h1>
      <p>{{ config.description }}</p>
      <button v-if="config.showButton">
        I am a Button
      </button>
  </div>
</template>
