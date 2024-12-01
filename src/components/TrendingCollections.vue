<script setup lang="ts">
</script>

<template>
  <div class="trending-section">
    <h2 class="title">Trending Collections</h2>
    <div class="cards">
      <div class="card">
        <h3>Trending</h3>
        <div class="list">
          <!-- Trending items will go here -->
        </div>
      </div>
      <div class="card">
        <h3>Hot Token</h3>
        <div class="list">
          <!-- Hot tokens will go here -->
        </div>
      </div>
      <div class="card">
        <h3>Hot Pair APR</h3>
        <div class="list">
          <!-- Hot pairs will go here -->
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.trending-section {
  margin-bottom: 32px;
}

.title {
  font-size: 24px;
  color: #FFFFFF;
  margin-bottom: 16px;
}

.cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 16px;
}

.card {
  background: #1A1A1A;
  border: 1px solid #2A2A2A;
  border-radius: 16px;
  padding: 24px;
}

h3 {
  color: #FFFFFF;
  font-size: 16px;
  margin: 0 0 16px 0;
  padding-bottom: 16px;
  border-bottom: 1px solid #2A2A2A;
}

.list {
  min-height: 200px;
}
</style>