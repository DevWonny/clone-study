<template>
  <div class="header-wrap">
    <div class="header-container">
      <div class="header-logo">
        <img src="~/static/header/header-logo.png" alt="Logo" />
      </div>

      <div class="menu-warp">
        <ul class="util-menu">
          <li>Sign In</li>
          <li>My Starbucks</li>
          <li>Customer Service &amp; Ideas</li>
          <li>Find a Store</li>
        </ul>

        <div class="search-container">search</div>

        <ul class="main-menu">
          <li>COFFEE</li>
          <li>MENU</li>
          <li>STORE</li>
          <li>RESPONSIBILITY</li>
          <li>STARBUCKS REWARDS</li>
          <li>CORPORATE SALES</li>
          <li>WHAT'S NEW</li>
        </ul>
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
  display: flex;
  justify-content: center;

  .header-container {
    width: 1100px;
    height: 100%;
    background: red;

    .header-logo {
      width: 75px;
      height: 75px;

      &img {
        width: 100%;
        height: 100%;
      }
    }

    .menu-wrap {
      width: 895px;
      height: 100%;
    }
  }
}
</style>
