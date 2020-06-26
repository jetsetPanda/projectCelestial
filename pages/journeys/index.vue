<template>
  <section>
    <section>
      <Heading
        headerName="The Journey Itself is the Destination"
        subHeaderName="Traverse the cosmos with our elite starcruiser fleet"
      />
    </section>

<!--    <h1 class="fontGalactic">Journeys with UpGalactic Starcruisers</h1>-->
<!--    <h2>The journey itself is the destination.</h2>-->
    <section class="journeys">

<!--      bind values to dynamic vals in API/demo data-->
      <Journey
        v-for="journey in FXjourneys"
        :key="journey.journeyid"
        :thumbnail="journey.thumbnail"
        :journeyName="journey.journeyName"
        :journeyTagline="journey.journeyTagline"
        :routeName="journey.routeName"
        :journeyDescription="journey.journeyDescription"
        :journeyid="journey.journeyid"
      />

<!--      <Journey-->
<!--        thumbnail="http://st-intelligence.com/ship_database/fed/images/Vcity_main.jpg"-->
<!--        journeyName="The Voth"-->
<!--        journeyTagline="Metropolis on a Ship"-->

<!--        routeName="Earth, UFP - Delta Quadrant"-->
<!--        journeyDescription="Best known for capturing the Federation starship USS Voyager in 2373, this citadel class starship can set you to stun with its majestic gravity simulated avenues and cityscapes."-->
<!--        journeyid="voth"-->
<!--      />-->

    </section>
  </section>
</template>

<script>
import Journey from '@/components/Journey'
import Heading from '@/components/Heading'

export default {
  components: {
    Journey,
    Heading,
  },
  asyncData() { //simulate an async req
    return new Promise((resolve, reject) => {
      setTimeout(() => {
        resolve({
          FXjourneys: [
            {
              id: "1",
              journeyid: "calamari",
              journeyName: "The Mon Calamari",
              journeyTagline: "Pampering, Rebel Style",
              routeName: "Coruscant - Endor (Round-Trip)",
              journeyDescription: "Travel in sheer luxury to a galaxy far far away with the Rebel Alliance's most famous frigate, now converted to a supremely relaxing resort cruiser.",
              thumbnail: "https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/770814e0-a7c0-4e13-aa31-107aed4dbaf6/dbpkbbj-5ff9a3d5-68cc-49d1-b79a-02bea83c7a93.jpg/v1/fill/w_1600,h_860,q_75,strp/mon_calamari_shipyards_mc85_command_cruiser_by_shoguneagle_dbpkbbj-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3siaGVpZ2h0IjoiPD04NjAiLCJwYXRoIjoiXC9mXC83NzA4MTRlMC1hN2MwLTRlMTMtYWEzMS0xMDdhZWQ0ZGJhZjZcL2RicGtiYmotNWZmOWEzZDUtNjhjYy00OWQxLWI3OWEtMDJiZWE4M2M3YTkzLmpwZyIsIndpZHRoIjoiPD0xNjAwIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmltYWdlLm9wZXJhdGlvbnMiXX0.TjAqcVXnuY3fqlR3A0wwSGkdtuhtBxJ5dhfDaPlYB50",
            },
            {
              id: "2",
              journeyid: "fhloston",
              journeyName: "Fhloston Paradise",
              journeyTagline: "Azure Escapade",
              routeName: "Mondoshawar - Earth 2263 (Hop-On, Hop-Off)",
              journeyDescription: "Graced with the voicecorder stylings of MC Ruby Rod, expect a fun and sensual lightwarp through the stars in this stylish vessel. The main highlight will be the showstopping performance by the Singular Azure Diva them-theyselves, Plavalaguna.",
              thumbnail: "https://i.imgur.com/wJWOWAw.jpg",
              // thumbnail: ["http://scifimoviezone.com/imagespaceopera/fifthelement020.jpg, "https://i.pinimg.com/564x/f5/28/08/f528084ac028c2af341c613298e68eb3.jpg",]
            },
            {
              id: "3",
              journeyid: "voth",
              journeyName: "The Voth",
              journeyTagline: "Metropolis on a Ship",
              routeName: "Earth, UFP - Delta Quadrant (One-Way)",
              journeyDescription: "Best known for capturing the Federation starship USS Voyager in 2373, this citadel class starship can set you to stun with its majestic gravity simulated avenues and cityscapes.",
              thumbnail: "http://st-intelligence.com/ship_database/fed/images/Vcity_main.jpg",
            },
          ]
        })
      }, 500)
    })
  },
};
</script>

<style scoped>
.journeys {
  margin-top: 50px;
  display: flex;
  flex-flow: wrap;
  justify-content: center;
  align-items: stretch;
}

.fontGalactic {
  color: #214774;
  font-size: 3rem;
  text-shadow: 1px 1px 2px #35495e;
}

</style>
