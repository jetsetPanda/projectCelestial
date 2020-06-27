<template>
  <div>
    <Navbar/>
    <Nuxt />
  </div>
</template>

<script>
  import Navbar from '@/components/Navbar'

  export default {
    components: {
      Navbar
    }
  }
</script>

<!--<link rel="stylesheet" href="https://use.typekit.net/did2oyx.css">-->

<style>
html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
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

.button--jetset {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #2F495E;
  color: #2F495E;
  text-decoration: none;
  padding: 10px 30px;
}

.button--jetset:hover {
  color: #fff;
  background-color: #E37200;
  border: 1px solid #E37200;
}

.button--github {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--github:hover {
  color: #fff;
  background-color: #35495e;
}

.uplogo {
  font-family: 'Audiowide', sans-serif;
  /*font-size: 72px;*/
  background: -webkit-linear-gradient(45deg, #09009f, #00ff95 80%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.upfont {
  font-family: 'Audiowide', sans-serif;
}

.jetsetfont {
  font-family: 'Righteous', sans-serif;
}
</style>
