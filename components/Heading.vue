<template>
  <div class="cont">
    <h1 class="fontGalactic">{{ headerName }}</h1>
    <h3>{{ subHeaderName }}</h3>
  </div>
</template>

<script>
  export default {
    props: ['headerName', 'subHeaderName',]
  }
</script>

<style scoped>
  .cont {
    margin: 60px 0px;
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  .fontGalactic {
    color: #214774;
    text-shadow: 1px 1px 2px #35495e;
  }

  h1 {
    font-size: 5em;
  }

  h3 {
    font-size: 2em;
  }

</style>
