<template>
  <div>
    <Header />
    <div class="main-container">
      <Nuxt />
    </div>
  </div>
</template>

<script>
import Header from '~/components/Header'
export default {
  components: {
    Header,
  },
}
</script>


<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
.main-container {
  padding-top: 7rem;
  max-width: 991px;
  margin: 0 auto;
  padding-left: 15px;
  padding-right: 15px;
  min-height: calc(100vh - 7rem);
}
</style>
