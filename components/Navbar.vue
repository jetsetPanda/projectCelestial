<template>
  <header>
    <nav>
      <ul>
        <li><nuxt-link to="/">Home</nuxt-link></li>
        <li><nuxt-link to="/journeys">Journeys</nuxt-link></li>
        <li><nuxt-link to="/experiences">Experiences</nuxt-link></li>
        <li><nuxt-link to="/about">About Us</nuxt-link></li>
        <li><nuxt-link to="/">Member Login</nuxt-link></li>
      </ul>
    </nav>
  </header>
</template>


<style scoped>
  header {
    width: 100%;
    height: 40px;
    background-color: #2D4266;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  a {
    text-decoration: none;
    font-size: 1.3em;
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

</style>
