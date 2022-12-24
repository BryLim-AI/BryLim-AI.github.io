<template>
  <div>
  <nav class="navigation">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/>
  <div class="sideNav">

    <a href="https://mail.google.com/mail/" target="_blank">
      <img class="side-icon" src="@/assets/e.png">
    </a>

    <a href="https://calendar.google.com/calendar?tab=wc&authuser=0" target="_blank">
      <img class="side-icon" src="@/assets/cal.png">
    </a>

    <a href="https://maps.google.com.ph/maps?hl=en&tab=wl&authuser=0" target="_blank">
      <img class="side-icon" src="@/assets/map.png">
    </a>

    <a href="https://fanyi.baidu.com/" target="_blank">
      <img class="side-icon" src="@/assets/tras.png">
    </a>

    <a href="https://www.google.com/" target="_blank">
      <img src="https://img.icons8.com/color/30/null/google-logo.png">
    </a>

    <a href="https://www.baidu.com/" target="_blank">
      <img src="https://img.icons8.com/color/30/null/baidu.png">
    </a>

  </div>
  </div>
</template>

<style lang="scss">
@import "./assets/styles.scss";

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
