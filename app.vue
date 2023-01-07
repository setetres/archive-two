<script setup lang="ts">
  const route = useRoute()
</script>
<template>
  <App>
    <NuxtLoadingIndicator color="#6366f1" />
    <Content>
      <NuxtPage />
    </Content>
    <Header />
  </App>
</template>
