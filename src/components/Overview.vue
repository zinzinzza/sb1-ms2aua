<script setup lang="ts">
</script>

<template>
  <div class="overview-section">
    <h2 class="title">Overview</h2>
    <div class="cards">
      <div class="card">
        <h3>Total Value Locked</h3>
        <div class="value">$235.01M</div>
        <div class="chart"></div>
      </div>
      <div class="card">
        <h3>Volume</h3>
        <div class="value">$2.45M</div>
        <div class="chart"></div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.overview-section {
  margin-bottom: 32px;
}

.title {
  font-size: 24px;
  color: #FFFFFF;
  margin-bottom: 16px;
}

.cards {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 16px;
}

.card {
  background: #1A1A1A;
  border: 1px solid #2A2A2A;
  border-radius: 16px;
  padding: 24px;
}

h3 {
  color: #828A90;
  font-size: 16px;
  margin: 0 0 8px 0;
}

.value {
  font-size: 34px;
  color: #FFFFFF;
  margin-bottom: 16px;
}

.chart {
  height: 200px;
  background: #2A2A2A;
  border-radius: 8px;
}
</style>