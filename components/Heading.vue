<template>
  <div class="cont">
    <h1 class="fontGalactic">{{ headerName }}</h1>
    <h2>{{ subHeaderName }}</h2>
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

  }

  h1 {
    font-size: 5em;
    color: #000000;
    text-shadow: 1px 1px 1px #181434;
  }

  h2 {
    font-size: 2.5em;
    color: #214774;
    text-shadow: 1px 1px 1px #4c96ae;
  }

</style>
