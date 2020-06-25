<template>
  <section>
    <h1 class="fontGalactic">Journeys with UP Galactic</h1>
    <h2>Let the journey itself be the destination.</h2>
    <section class="journeys">

      <Journey
        thumbnail="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/770814e0-a7c0-4e13-aa31-107aed4dbaf6/dbpkbbj-5ff9a3d5-68cc-49d1-b79a-02bea83c7a93.jpg/v1/fill/w_1600,h_860,q_75,strp/mon_calamari_shipyards_mc85_command_cruiser_by_shoguneagle_dbpkbbj-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3siaGVpZ2h0IjoiPD04NjAiLCJwYXRoIjoiXC9mXC83NzA4MTRlMC1hN2MwLTRlMTMtYWEzMS0xMDdhZWQ0ZGJhZjZcL2RicGtiYmotNWZmOWEzZDUtNjhjYy00OWQxLWI3OWEtMDJiZWE4M2M3YTkzLmpwZyIsIndpZHRoIjoiPD0xNjAwIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmltYWdlLm9wZXJhdGlvbnMiXX0.TjAqcVXnuY3fqlR3A0wwSGkdtuhtBxJ5dhfDaPlYB50"
        journeyName="The Mon Calamari Starcruiser"
        routeName="Coruscant - Endor"
        journeyDescription="Travel to a galaxy far far away with the Rebel Alliance's most famous frigate, now converted to a supremely luxurious frigate spa resort."
      />

      <article class="journey">
        <div class="thumbnail" style="background-image: url('http://st-intelligence.com/ship_database/fed/images/Vcity_main.jpg')")></div>
        <h1>Voth: City on a Ship</h1>
        <h4>(Earth, UFP - Delta Quadrant)</h4>
        <p>Best known for capturing the Federation starship USS Voyager in 2373, this citadel class ship can set you to stun with its majestic gravity enabled avenues and cityscapes.</p>
      </article>


    </section>
  </section>
</template>

<script>
  import Journey from '@/components/Journey'

  export default {
    components: {
      Journey
    }
  }
</script>

<style scoped>
.journeys {
  margin-top: 50px;

  display: flex;
  flex-flow: wrap;
  justify-content: center;
  /*align-items: center;*/
}

.fontGalactic {
  color: #214774;
  font-size: 3rem;
}

.journey {
  margin: 17px;
  box-sizing: border-box;
  width: 350px;
  padding: 25px;
  border: 1px solid #CCCCCC;
  border-radius: 10%;
  box-shadow: 1px 1px 5px #214774;
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
