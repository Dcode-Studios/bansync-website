<template>
  <div class="home">
    <b-container>

      <b-row class="">
        <b-col cols="8" offset="2">
          <b-jumbotron header="BanSync" style="background-color: #01E8B9;"
          lead="Help keep out possible troublemakers from your server by knowing user's previous bans, or by linking your servers together to sync bans within them.">
          </b-jumbotron>
        </b-col>
      </b-row>

      <b-row>

        <b-col cols="8">
          <b-row>
            <b-cols>
              <div>
                <b-carousel
                  class="mb-4"
                  id="carousel-1"
                  v-model="slide"
                  :interval="4000"
                  controls
                  indicators
                  background="#ababab"
                  style="text-shadow: 1px 1px 2px #333;"
                  img-height="480"
                >
                  <!-- Text slides with image -->
                  <b-carousel-slide img-height="480" img-src="/gallery/1.png"></b-carousel-slide>
                  <b-carousel-slide img-src="/gallery/2.png"></b-carousel-slide>
                  <b-carousel-slide img-src="/gallery/3.png"></b-carousel-slide>
                </b-carousel>
              </div>
            </b-cols>
          </b-row>
          <b-row>
            <b-cols>
              <b-row>
                <b-col cols="12">
                  <b-card no-body class="palette-2 text-center mb-4 pt-2 text-white"><h3><b>Features</b></h3></b-card>
                </b-col>
              </b-row>
              <b-row>
                <b-col cols="6" class="mb-4" v-for="feature in this.features" v-bind:key="feature">
                    <b-card bg-variant="light" text-variant="dark" :header="feature.title" class="text-center">
                      <b-card-text>{{feature.text}}</b-card-text>
                    </b-card>
                </b-col>
              </b-row>
            </b-cols>
          </b-row>
        </b-col>

        <b-col cols="4">

          <b-row>
            <b-col cols="12">
              <b-card no-body class="palette-2 text-center mb-4 pt-2 text-white"><h3><b>The Team</b></h3></b-card>
            </b-col>
          </b-row>
          <b-row>
            <b-col cols="6" v-for="member in this.crew" v-bind:key="member.name" class="mb-4">
              <custommember :img="member.imgUrl" :crewname="member.name" :red="member.redirect" />
            </b-col>
          </b-row>
        </b-col>
      </b-row>


      <b-row>
        <b-col cols="12">
          <b-card no-body class="palette-2 text-center mb-4 pt-2 text-white"><h3><b>As seen on</b></h3></b-card>
        </b-col>
      </b-row>
      <b-row class="pb-5 text-center">
        <b-col cols="4">
          <b-img thumbnail src="https://top.gg/api/widget/743234197484994610.svg"></b-img>
        </b-col>
        <b-col cols="4">
          <b-img thumbnail src="https://botsfordiscord.com/api/bot/743234197484994610/widget"></b-img>
        </b-col>
        <b-col cols="4">
          <b-img thumbnail src="https://discord.boats/api/widget/743234197484994610"></b-img>
        </b-col>
      </b-row>

    </b-container>
  </div>
</template>

<script>
// @ is an alias to /src
import custommember from '../components/Member.vue'
export default {
  name: 'Home',
  components: {
    custommember
  },
  data: function (){
    return {
      crew: [
        {
          "imgUrl": "/avatars/techgeekgamer.png",
          "name": "TechGeekGamer#7205",
          "redirect": "https://github.com/TechGeekGamer"
        },
        {
          "imgUrl": "/avatars/hax4dayz.png",
          "name": "hax4dayz#9094",
          "redirect": "https://github.com/hax4dazy"
        },
        {
          "imgUrl": "/avatars/megaglitch.png",
          "name": "MegaGlitch#7060",
          "redirect": "https://github.com/TheMegaGlitch"
        },
        {
          "imgUrl": "/avatars/orangegroup.png",
          "name": "OrangeGroup#5362",
          "redirect": "https://github.com/orangegrouptech"
        },
        {
          "imgUrl": "/avatars/alex.png",
          "name": "alex.",
          "redirect": "https://twitter.com/alexgsm60hz"
        },
        {
          "imgUrl": "/avatars/elijah.jpg",
          "name": "ElijahC06",
          "redirect": "https://github.com/ElijahC06"
        },
        {
          "imgUrl": "/avatars/adelaide.jpg",
          "name": "adelaide",
          "redirect": "https://www.reddit.com/u/ScarlettDawnnn"
        },
        {
          "imgUrl": "/avatars/slluxx.png",
          "name": "Snyv#7598",
          "redirect": "https://github.com/slluxx"
        }
      ],
      features: [
        {
          "title": "Linked Servers",
          "text": "Linked Servers is a feature BanSync has to allow you to link up your servers to have bans synced within them. This means that if someone gets banned from one of the servers, they'll automatically be banned and blacklisted from all the linked servers."
        },
        {
          "title": "Global Ban Reason Database",
          "text": "BanSync has a feature that tracks bans you make, and shares information about it to other servers. This feature is optional and is disabled by default. This can be enabled/disabled via the &settings command."
        },
        {
          "title": "/ Slash Commands",
          "text": "BanSync has work in progress Slash Commands, but more are to come!"
        },
        {
          "title": "Active Development",
          "text": "BanSync is in active development and new features are being developed all the time."
        }
      ]
    }
  }
}
</script>

<style scoped>
.palette-2 {
  background-color: #01a293;
}
</style>