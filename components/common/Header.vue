<template>
  <div class="header-wrap">
    <div class="header-container">
      <div class="header-logo">
        <img src="~/static/header/header-logo.png" alt="Logo" />
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped lang="scss">
.header-wrap {
  width: 100%;
  height: 120px;
  border: 1px solid red;
  box-sizing: border-box;

  .header-container {
    width: 1100px;
    height: 100%;
    background: red;
  }
}
</style>
