<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title uplogo">
        UP:Galactic
      </h1>
      <h2 class="upfont">On-Demand : Luxury : Starcruiser Fleet</h2>
      <div class="links">
        <a
          href="https://jetsetengine.netlify.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--jetset "
        >
          a <span class="jetsetfont">jetsetEngine</span> joint
        </a>
        <a
          href="https://github.com/jetsetPanda"
          target="_blank"
          rel="noopener noreferrer"
          class="button--github"
        >
          Github Repo
        </a>
      </div>
    </div>
  </div>
</template>

<script>
  export default {

  }
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #214774;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 55px;
}


</style>
