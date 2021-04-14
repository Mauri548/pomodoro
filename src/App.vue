<template>
  <router-view class="application__container" />
</template>

<style lang="scss">
@import './style/reset.scss';
@import './style/layout.scss';
body {
  padding: 0;
  margin: 0;
  // Css Variables
  // Color
  --application-color-primary: #E23434;
  --application-color-accent: #333745;
  --application-color-text: #fff;
}

* {
  box-sizing: border-box;
}

#app {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica,
                Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
