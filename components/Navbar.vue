<template>
  <header>
    <div class="upfont logo"><nuxt-link to="/"><span class="upfont logo">UP:Galactic</span></nuxt-link></div>
<!--    <nuxt-link to="/"><span class="upfont logo">UP:Galactic</span></nuxt-link>-->
    <nav>
      <ul class="nav_links">
        <li><nuxt-link to="/journeys">Journeys</nuxt-link></li>
        <li><nuxt-link to="/experiences">Experiences</nuxt-link></li>
        <li><nuxt-link to="/about">About <span class="upfont">UP</span></nuxt-link></li>
      </ul>
    </nav>
    <nuxt-link to="/" class="btn upfont">Login</nuxt-link>
  </header>
</template>


<style scoped>
  /** {*/
  /*  box-sizing: border-box;*/
  /*  margin: 0;*/
  /*  padding: 0;*/
  /*}*/

  header {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    padding: 1.5vh 5%;
    background-color: #0e1420;

  }

  .logo {
    cursor: pointer;
    margin-right: auto;
    font-size: 1.4em;
    background: white;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    transition: all 0.3s ease 0s;
  }

  .logo a {
    text-decoration: none;
    font-size: 1.3em;
    color: #FFFFFF;


  }

  .logo:hover {
    background: -webkit-linear-gradient(45deg, #0d00e2, #00ff95 80%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    transition: all 0.3s ease 0s;
  }

  .nav_links {
    list-style: none;
  }

  .nav_links li {
    display: inline-block;
    padding: 0px 20px;
  }

  a {
    text-decoration: none;
    font-size: 1.3em;
    color: #FFFFFF;
    transition: all 0.3s ease 0s;
  }

  .nav_links a:hover {
    color: orange;
  }

  .btn {
    font-size: 1em;
    margin-left: 30px;
    padding: 10px 15px;
    background-color: #4CA4BC;
    border: none;
    border-radius: 0px 15px 0px 15px;
    cursor: pointer;
    transition: all 0.3s ease 0s;
    /*box-shadow: 1px 1px 1px #2663ad;*/
    color: black;
  }

  .btn:hover {
    background-color: rgba(0,136,169,0.7);
    color: white;
  }
</style>
