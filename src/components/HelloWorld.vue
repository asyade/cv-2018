<template>
  <v-container container-main grid-list-md text-xs-center>
    <vue-particles  color="#0c907d" :particleOpacity="0.7" :particlesNumber="80" shapeType="circle" :particleSize="4" linesColor="#0c907d" :linesWidth="1" :lineLinked="true" :lineOpacity="0.4" :linesDistance="150" :moveSpeed="3" :hoverEffect="false"  :clickEffect="false" style="position: absolute; left: 0px; top: 0px; width: 100%; height: 100%; background-color: #113a5d;" id="particles-js"></vue-particles>
    <v-layout row wrap>
      <v-flex xs12 md8>
        <v-layout row wrap>
          <v-flex class="bounce-in-top" xs-12>
            <v-card>
              <v-card-text>
                <v-layout row>
                  <v-flex style="max-height: 140px; max-width: 140px; min-height: 120px; min-width: 120px;" xs2>
                      <img
                      style="width: 90%; min-height: 120px; min-width: 120px;"
                      :src="require('../assets/profil.jpg')"
                      />
                  </v-flex>
                  <v-flex xs8 text-xs-left style="max-height: 170px;">
                    <div style="position: relative; height: 100%; width: 100%; min-height: 120px;">
                      <v-subheader>
                        <span>
                          <span style="font-size: 1.2em;">Asya Corbeau, 20 Ans</span>
                          <br/>
                          FullStack devlopper
                          <br/>
                          Paris 20
                        </span>
                      </v-subheader>
                      <v-subheader style="position: absolute; bottom: 0;margin-top: 5px; font-size: .9em;">
                        <p>
                        <a href="phoneto:00665509956">TÉLÉPHONE 0664409956</a>
                        <br>
                        <a href="mailto:zarandifar@gmail.com">MAIL zarandifar@gmail.com</a>
                        <br>
                        <a href="mailto:zarandifar@gmail.com">LinkedIn</a><span> | </span>
                        <a href="mailto:zarandifar@gmail.com">Github</a>
                        </p>
                      </v-subheader>
                    </div>
                  </v-flex>
                </v-layout>
              </v-card-text>
            </v-card>
          </v-flex>
          <v-flex bounce-in-bottom xs12>
            <v-card>
              <v-card-text>
                <v-timeline dense clipped >
                  <v-timeline-item  small class="mb-3" color="#0c907d" >
                    <v-layout text-xs-left justify-space-between>
                      <v-flex xs10>
                        <v-subheader>Ecole 42</v-subheader>
                        <p style="padding: 0em 1em;">Mis a part les projet de l'ecole j'ai participer a plusieurs hackaton (Consult'in france 1st, Respir hacktion 2st, Etonomy 2st), maintenant en fin de cursus j'etudie principalement la programmation système</p>
                      </v-flex>
                      <v-flex font-italic caption xs2 text-xs-right>Depuis 2017</v-flex>
                    </v-layout>
                  </v-timeline-item>  
                  <v-timeline-item  color="#0c907d"  class="mb-3"  small>
                    <v-layout text-xs-left justify-space-between>
                      <v-flex xs10>
                        <v-subheader>Seed-up - STAGE</v-subheader>
                        <p style="padding: 0em 1em;">Stage de 6 mois durant les quelle je me suis familiariser avec l'intgration continue, la methode agile et l'ecosysteme aws par le biais de plusieurs application et programmes de test</p>
                      </v-flex>
                      <v-flex font-italic caption xs2 text-xs-right>11/2017 05/2018</v-flex>
                    </v-layout>
                  </v-timeline-item>
                  <v-timeline-item color="#0c907d" small>
                    <v-layout text-xs-left justify-space-between>
                      <v-flex xs10>
                        <v-subheader>MOORE - CDD</v-subheader>
                        <p style="padding: 0em 1em;">Devloppement de moore, un filesysteme connectee au cloud utilisant un AI, il vise principalement le marchee du mobile c'est pourquoi nous il est devlopper pour Android, principalement en RUST et du JAVA</p>
                      </v-flex>
                      <v-flex font-italic caption xs2 text-xs-right>05/2018 09/2018</v-flex>
                    </v-layout>
                  </v-timeline-item>
                  <v-timeline-item color="#0c907d" small>
                    <v-layout text-xs-left justify-space-between>
                      <v-flex xs10>
                        <v-subheader>The wizzard - Projet</v-subheader>
                        <p style="padding: 0em 1em;">Nous devloppons des algorythme de prediction sur le marchee des cryptomonnais, actuellement le POC d'un outils utilisant ces algorytme, est disponible</p>
                      </v-flex>
                      <v-flex font-italic caption xs2 text-xs-right>Depuis 10/2018</v-flex>
                    </v-layout>
                  </v-timeline-item>
                  <v-timeline-item  color="#0c907d" class="mb-3"  small>
                    <v-layout text-xs-left justify-space-between>
                      <v-flex xs10><v-subheader>Freelance (Devloppeur web)</v-subheader>
                      <v-card-text>Jai effectuer plusieurs mission web et ai completement devlopper les sites suivant <br><a href="http://cosm-xskateboard.com">cosm-xskateboard.com</a>, <a href="http://helpjivan.org/">helpjivan.org</a>, <a href="http://www.aquareden.fr">aquareden.fr</a> et <a href="https://jeuduroi.fr">jeuduroi.fr</a></v-card-text></v-flex>
                      <v-flex font-italic caption xs2 text-xs-right>Entre 2015 et 2017</v-flex>
                    </v-layout>
                  </v-timeline-item>
                </v-timeline>
              </v-card-text>
            </v-card>
          </v-flex>
          <v-flex xs12 text-xs-left roll-in-right>
            <v-card>
              <v-card-title>
                <v-subheader>
                Qui suije ?
                </v-subheader>
              </v-card-title>
              <v-card-text style="padding: 0em 2.2em 2em 2.2em;">
                Passionner de programmation je n'ai de sesse de devlopper mes competences, je prendre le temps de faire du code de qualitee et je suis curieux, toujour a la recherche des meilleurs alternative.<br/>
                Mon atout principale est ma capacitee a apprendre, pour moi utiliser une nouvelle techno, un nouveau framweork ou un outils inconnue est un divertisement plus qu'une corvee</br>
                Tres autonome mais egalement alaise en groupe je suis capable de concevoire et de devlopper des infrastructure complexe, adaptee et adaptative.
              </v-card-text>
            </v-card>
          </v-flex>
        </v-layout>
      </v-flex>
      <v-flex xs12 md4 text-xs-left roll-in-right>
        <v-card>
          <v-card-text>
            <v-list>
              <template v-for="item in skills">
                <v-subheader v-bind:key=item.name>{{ item.name }}</v-subheader>
                <v-list-tile v-bind:key=sub.id v-for="sub in item.children">
                  <span style="font-size: 1em;">{{ sub.name }}</span>
                </v-list-tile>
              </template>
            </v-list>
          </v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>

  export default {
    data: () => ({
      skills: [
      {
        id: 1,
        name: 'Programmation système',
        children: [
          { id: 1, name: 'C' },
          { id: 2, name: 'C++' },
          { id: 3, name: 'Rust' },
        ]
      },
      {
        id: 2,
        name: 'Prototypage et applicatif',
        children: [
          { id: 1, name: 'Python' },
          { id: 2, name: 'C#/Wpf/ASP' },
          { id: 3, name: 'Java/Android' },
          { id: 4, name: 'Arduino' },
          { id: 5, name: 'Bash' },
        ]
      },
      {
        id: 3,
        name: 'Programmation Web',
        children: [
          { id: 1, name: 'HTML/CSS/PHP' },
          { id: 2, name: 'Asp.net' },
          { id: 2, name: 'NodeJS' },
          { id: 3, name: 'Django' },
        ]
      },
      {
        id: 4,
        name: 'Lib/Framwork/Techno',
        children: [
          { id: 1, name: 'CCXT' },
          { id: 2, name: 'Vue.js' },
          { id: 3, name: 'React/Redux' },
          { id: 4, name: 'Electron/Ionic/Cordova' },
          { id: 5, name: 'Pandas/RustLearn' },
          { id: 6, name: 'SqlLite/MySql' },
          { id: 7, name: 'Open LDAP' },
          { id: 8, name: 'OpenGL/OpenCL' },
          { id: 9, name: 'Rocker/Express/Nancy' },
        ]
      },
      {
        id: 5,
        name: "Outils",
        children: [
          { id: 1, name: 'Git' },
          { id: 2, name: 'GitLab CI' },
          { id: 3, name: 'Docker' },
          { id: 4, name: 'Photoshop/Gimp' },
          { id: 5, name: 'Cura/Repetier' },
          { id: 6, name: 'Inventor/Freecad' },
        ]
      }
      ]
    })
  }
</script>

<style>
.v-timeline-item__dot {
padding: 20px;
}
.theme--dark.v-list, .theme--dark.v-card {
  background-color: #062743 !important;
}
.v-list__tile {
  height: 40px;
}
a:visited, a {
  color: #f9f9f9 !important;
  text-decoration: none;
  border-bottom: 1px dashed #0c907d;
}
.theme--dark.v-subheader {
    color: #0c907d !important; 
}
.theme--dark.v-card, .v-list__tile {
  color: #f9f9f9 !important;
}



.bounce-in-top, .bounce-in-bottom, .roll-in-right {
	-webkit-animation: slide-in-top 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) .3s both;
	        animation: slide-in-top 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) .3s both;
}
@-webkit-keyframes slide-in-top {
  0% {
    -webkit-transform: translateY(-1000px);
            transform: translateY(-1000px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    opacity: 1;
  }
}
@keyframes slide-in-top {
  0% {
    -webkit-transform: translateY(-1000px);
            transform: translateY(-1000px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    opacity: 1;
  }
}

.container-main {
  max-width: 900px;
  min-width: 460px;
}


</style>
