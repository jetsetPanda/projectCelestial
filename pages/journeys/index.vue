<template>
  <section>
    <h1 class="fontGalactic">Journeys with UP Galactic Starcruisers</h1>
    <h2>The journey itself is the destination.</h2>
    <section class="journeys">

      <Journey
        thumbnail="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/770814e0-a7c0-4e13-aa31-107aed4dbaf6/dbpkbbj-5ff9a3d5-68cc-49d1-b79a-02bea83c7a93.jpg/v1/fill/w_1600,h_860,q_75,strp/mon_calamari_shipyards_mc85_command_cruiser_by_shoguneagle_dbpkbbj-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3siaGVpZ2h0IjoiPD04NjAiLCJwYXRoIjoiXC9mXC83NzA4MTRlMC1hN2MwLTRlMTMtYWEzMS0xMDdhZWQ0ZGJhZjZcL2RicGtiYmotNWZmOWEzZDUtNjhjYy00OWQxLWI3OWEtMDJiZWE4M2M3YTkzLmpwZyIsIndpZHRoIjoiPD0xNjAwIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmltYWdlLm9wZXJhdGlvbnMiXX0.TjAqcVXnuY3fqlR3A0wwSGkdtuhtBxJ5dhfDaPlYB50"
        journeyName="The Mon Calamari"
        journeyTagline="Pampering, Rebel Style"
        routeName="Coruscant - Endor"
        journeyDescription="Travel to a galaxy far far away with the Rebel Alliance's most famous frigate, now converted to a supremely luxurious resort starcruiser."
      />

      <Journey
        thumbnail="https://i.pinimg.com/564x/f5/28/08/f528084ac028c2af341c613298e68eb3.jpg"
        journeyName="Fhloston Paradise"
        journeyTagline="Azure Escapade"
        routeName="Mondoshawar - Earth 2263"
        journeyDescription="Hosted by the voicecorder stylings of MC Ruby Rod, expect a fun and sensual lightwarp through the galaxy at this stylish starliner. The main highlight will be the showstopping performance by the Azure Diva themselves, Plavalaguna."
      />

      <Journey
        thumbnail="http://st-intelligence.com/ship_database/fed/images/Vcity_main.jpg"
        journeyName="The Voth"
        journeyTagline="City on a Ship"

        routeName="Earth, UFP - Delta Quadrant"
        journeyDescription="Best known for capturing the Federation starship USS Voyager in 2373, this citadel class ship can set you to stun with its majestic gravity simulated avenues and cityscapes."
      />

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

</style>
