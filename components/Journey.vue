<template>
  <nuxt-link :to="'/journeys/' + journeyid">
    <article class="journey">
      <div
        class="thumbnail"
        :style="{backgroundImage: 'url(' + thumbnail + ')'}"
      ></div>
      <h1 class="journey-name">{{ journeyName }}</h1>
      <h1>{{ journeyTagline}}</h1>
      <h3>{{ routeName }}</h3>
    </article>
  </nuxt-link>
</template>

<script>
  export default {
    props: [
      'thumbnail',
      'journeyName',
      'journeyTagline',
      'routeName',
      'journeyDescription',
      'journeyid'
    ]
  }
</script>


<style scoped>

  h1 {
    font-size: 1.5em;
    text-shadow: 1px 1px 1px #35495e;
  }

  p {
    font-size: 1.1em;
  }

  a {
    text-decoration: none;
    color: #000000;
  }

  .journey {
    margin: 17px;
    box-sizing: border-box;
    width: 25vw;
    padding: 25px;
    border: 1px solid #CCCCCC;
    border-radius: 0% 10% 0% 10%;
    box-shadow: 1px 2px 5px #214774;
  }

  .journey-name {
    font-size: 3em;
  }

  .thumbnail {
    background-position: center;
    background-size: cover;
    height: 30vh;
    -webkit-transition:height 300ms;
    -moz-transition:height 300ms;
    transition:height 300ms;
    border-radius: 0% 12% 0% 0%;
    box-shadow: 2px 2px 3px #214774;
  }

  .thumbnail:hover {
    height: 40vh;
  }


</style>
