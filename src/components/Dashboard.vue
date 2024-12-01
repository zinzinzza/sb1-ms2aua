<script setup lang="ts">
import { ref } from 'vue'
import TopBar from './TopBar.vue'
import Overview from './Overview.vue'
import TrendingCollections from './TrendingCollections.vue'

const count = ref(0)
</script>

<template>
  <div class="dashboard-container">
    <TopBar />
    <div class="dashboard-content">
      <Overview />
      <TrendingCollections />
    </div>
  </div>
</template>

<style scoped>
.dashboard-container {
  width: 100%;
  min-height: 100vh;
  background: #0A0A0A;
}

.dashboard-content {
  padding: 24px;
  max-width: 1440px;
  margin: 0 auto;
}
</style>