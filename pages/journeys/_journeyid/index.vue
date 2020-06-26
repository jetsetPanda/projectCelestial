<template>
<!--  e.g. below: dynamic route in vue router-->
<!--  <p>{{ $route.params.shipid }}</p>-->
  <section class="single-journey">
    <h1>{{ $route.params.journeyid }}</h1>
    <div>
      <img src="" alt="">
    </div>
    <p>Ship description</p>
  </section>
</template>

<style scoped>

  .single-journey {
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 35px;
    border: 1px solid #CCCCCC;
    border-radius: 0% 10% 0% 10%;
    /*-webkit-transition:border-radius 300ms;*/
    /*-moz-transition:border-radius 300ms;*/
    /*transition:border-radius 300ms;*/
    box-shadow: 1px 2px 5px #214774;
  }
</style>
