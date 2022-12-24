<template>
  <div>
  <nav class="navigation">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/>
  <div class="sideNav">

    <a href="" target="_blank">
      <img class="side-icon" src="@/assets/e.png">
    </a>

    <a href="" target="_blank">
      <img class="side-icon" src="@/assets/cal.png">
    </a>

    <a href="" target="_blank">
      <img class="side-icon" src="@/assets/map.png">
    </a>

    <a href="" target="_blank">
      <img class="side-icon" src="@/assets/tras.png">
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
