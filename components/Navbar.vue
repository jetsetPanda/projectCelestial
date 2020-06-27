<template>
  <header>
    <nav>
      <ul>
        <li><nuxt-link to="/"><span class="upfont logo">UP:Galactic</span></nuxt-link></li>
        <li><nuxt-link to="/journeys" >Journeys</nuxt-link></li>
        <li><nuxt-link to="/experiences">Experiences</nuxt-link></li>
        <li><nuxt-link to="/about">About <span class="upfont">UP</span></nuxt-link></li>
        <li><nuxt-link to="/">Member Login</nuxt-link></li>
      </ul>
    </nav>
  </header>
</template>


<style scoped>
  header {
    width: 100%;
    height: 60px;
    background-color: #2D4266;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  a {
    display: block;
    text-decoration: none;
    font-size: 1.2em;
    color: #FFFFFF;
  }

  ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  li {
    margin: 0 12px;
  }

  .logo {
    flex: 1;
    font-size: 1.6em;
    /*text-shadow: 1px 1px 1px #000000;*/
  }
</style>
