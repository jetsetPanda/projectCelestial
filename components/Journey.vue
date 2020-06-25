<template>
  <article class="journey">
    <div
      class="thumbnail"
      :style="{backgroundImage: 'url(' + thumbnail + ')'}"
    ></div>
    <h1>{{ journeyName }}</h1>
    <h4>{{ routeName }}</h4>
    <p>{{ description }}</p>
  </article>
</template>

<script>
  export default {
    props: ['thumbnail, journeyName, routeName, description']
  }
</script>
