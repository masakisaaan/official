<template>
  <div class="root">
    <app-logo />
    <app-menu />
    <nuxt />
    <app-footer />
  </div>
</template>

<script>
  import appLogo from '~/components/app-logo'
  import appMenu from '~/components/app-menu'
  import appFooter from '~/components/app-footer'
  export default {
    components: {
      appLogo,
      appMenu,
      appFooter,
    },
  }
</script>

<style>
  html {
    font-size: 15px;
    -ms-text-size-adjust: 100%;
    -webkit-text-size-adjust: 100%;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    -webkit-font-smoothing: antialiased;
    color: #000;
    word-spacing: 1.5px;
    box-sizing: border-box;
    background-color: #fff;
    font-family:"Yu Gothic Medium", "游ゴシック Medium", YuGothic, "游ゴシック体", "ヒラギノ角ゴ Pro W3", "メイリオ", sans-serif;
  }

  *, * before, * after {
    box-sizing: border-box;
    margin: 0;
    max-width: 100%;
    text-decoration: none;
    color: #000;
  }

  ::selection {
    background: #009688;
    color: #fff;
  }

  .root {
    position: relative;
  }
</style>
