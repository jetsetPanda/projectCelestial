<template>
  <article class="journey">
    <div
      class="thumbnail"
      :style="{backgroundImage: 'url(' + thumbnail + ')'}"
    ></div>
    <h1>{{ journeyName }}</h1>
    <h4>{{ routeName }}</h4>
    <p>{{ journeyDescription }}</p>
  </article>
</template>

<script>
  export default {
    props: ['thumbnail', 'journeyName', 'routeName', 'journeyDescription']
  }
</script>


<style scoped>
  .journey {
    margin: 17px;
    box-sizing: border-box;
    width: 350px;
    padding: 25px;
    border: 1px solid #CCCCCC;
    border-radius: 10%;
    box-shadow: 1px 2px 3px #214774;
  }

  .thumbnail {
    background-position: center;
    background-size: cover;
    height: 100%;
    height: 200px;
    border-radius: 2%;
    box-shadow: 1px 1px 1px #47494E;
  }

</style>
