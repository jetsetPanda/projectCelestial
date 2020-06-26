<template>
  <article class="journey">
    <div
      class="thumbnail"
      :style="{backgroundImage: 'url(' + thumbnail + ')'}"
    ></div>
    <h1>{{ journeyName }}:</h1>
    <h1>{{ journeyTagline}}</h1>
    <h3>{{ routeName }}</h3>
    <br/>
    <p>{{ journeyDescription }}</p>
  </article>
</template>

<script>
  export default {
    props: ['thumbnail', 'journeyName', 'journeyTagline','routeName', 'journeyDescription']
  }
</script>


<style scoped>
  .journey {
    margin: 17px;
    box-sizing: border-box;
    width: 400px;
    padding: 25px;
    border: 1px solid #CCCCCC;

    border-top-right-radius: 5%;
    border-bottom-left-radius: 5%;
  ;
    box-shadow: 1px 2px 5px #214774;
  }

  h1 {
    font-size: 1.5em;
    text-shadow: 1px 1px 1px #35495e;
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
