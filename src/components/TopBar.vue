<script setup lang="ts">
</script>

<template>
  <div class="topbar-pc">
    <img src="/vite.svg" class="logo-wemax-color-01" alt="WEMAX logo" />
    <div class="spacer"></div>
    <div class="topbar-menu-group">
      <div class="topbar-menu">
        <div class="dashboard">Dashboard</div>
      </div>
      <div class="topbar-menu">
        <div class="swap">Swap</div>
      </div>
      <div class="topbar-menu">
        <div class="pool">Pool</div>
      </div>
      <div class="topbar-menu">
        <div class="staking">Staking</div>
      </div>
      <div class="topbar-menu">
        <div class="lending">Lending</div>
      </div>
    </div>
    <div class="spacer"></div>
    <div class="frame-1597888347">
      <div class="tobbar-btn">
        <div class="connect-wallet">Connect Wallet</div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.topbar-pc {
  height: 80px;
  display: flex;
  align-items: center;
  padding: 16px 24px;
  background: #1A1A1A;
  border-bottom: 1px solid #2A2A2A;
}

.logo-wemax-color-01 {
  height: 32px;
}

.spacer {
  flex: 1;
}

.topbar-menu-group {
  display: flex;
  gap: 32px;
}

.topbar-menu {
  height: 48px;
  display: flex;
  align-items: center;
  color: #FFFFFF;
  font-size: 15px;
  cursor: pointer;
}

.tobbar-btn {
  padding: 11px 16px;
  background: #385CF2;
  border-radius: 100px;
  color: #FFFFFF;
  cursor: pointer;
}

.connect-wallet {
  font-size: 15px;
}
</style>