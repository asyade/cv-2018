<template>
  <v-container container-main grid-list-md text-xs-center>
    <vue-particles  color="#0c907d" :particleOpacity="0.7" :particlesNumber="80" shapeType="circle" :particleSize="4" linesColor="#0c907d" :linesWidth="1" :lineLinked="true" :lineOpacity="0.4" :linesDistance="150" :moveSpeed="3" :hoverEffect="false"  :clickEffect="false" style="position: absolute; left: 0px; top: 0px; width: 100%; height: 100%; background-color: #113a5d;" id="particles-js"></vue-particles>
    <transition name="fade">
    <v-layout v-if="main" row wrap>
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
                      <v-subheader style="padding-top: 10px;">
                        <span>
                          <span style="font-size: 1.2em;">Asya Corbeau, 20 Ans</span>
                          <br/>
                          Full stack developer
                          <br/>
                          Paris 20
                        </span>
                      </v-subheader>
                      <v-subheader style="position: absolute; bottom: 0;margin-top: 5px; font-size: .9em;">
                        <p>
                        <a class="swing-in-top-fwd" href="phoneto:000658545246">TÉLÉPHONE 0658545246</a>
                        <br>
                        <a class="swing-in-top-fwd" href="mailto:zarandifar@gmail.com">EMAIL zarandifar@gmail.com</a>
                        <br>
                        <a class="swing-in-top-fwd" href="https://www.linkedin.com/in/asya-corbeau-4ab9ba151/">LinkedIn</a><span> | </span>
                        <a class="swing-in-top-fwd" href="https://github.com/asyade">Github</a>
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
                        <v-subheader>École 42</v-subheader>
                        <p style="padding: 0em 1em;">En parallèle des projets proposer par l'école j'ai participé a plusieurs hackatons (Consult'in France 1st, Respire hacktion 3st, E-Tonomy 3st).</br>Maintenant en fin de cursus j'étudie principalement la programmation système</p>
                      </v-flex>
                      <v-flex font-italic caption xs2 text-xs-right>Depuis 2017</v-flex>
                    </v-layout>
                  </v-timeline-item>  
                  <v-timeline-item  color="#0c907d"  class="mb-3"  small>
                    <v-layout text-xs-left justify-space-between>
                      <v-flex xs10>
                        <v-subheader>Seed-up - STAGE</v-subheader>
                        <p style="padding: 0em 1em;">Durant ce stage, je me suis familiarisé avec l'intégration continue, la méthode agile et l'écosystème AWS par le biais de plusieurs applications et programmes de test</p>
                      </v-flex>
                      <v-flex font-italic caption xs2 text-xs-right>11/2017 05/2018</v-flex>
                    </v-layout>
                  </v-timeline-item>
                  <v-timeline-item color="#0c907d" small>
                    <v-layout text-xs-left justify-space-between>
                      <v-flex xs10>
                        <v-subheader>MOORE - CDD</v-subheader>
                        <p style="padding: 0em 1em;">J'ai participé à la réécriture du prototype de MOORE, un filesystem connecté au cloud utilisant un apprentissage intelligent. Il vise principalement le marché du mobile c'est pourquoi il a été réécrit pour Android en RUST</p>
                      </v-flex>
                      <v-flex font-italic caption xs2 text-xs-right>05/2018 09/2018</v-flex>
                    </v-layout>
                  </v-timeline-item>
                  <v-timeline-item color="#0c907d" small>
                    <v-layout text-xs-left justify-space-between>
                      <v-flex xs10>
                        <v-subheader>The wizzard - Projet</v-subheader>
                        <p style="padding: 0em 1em;">Nous développons des algorithmes de prédiction sur le marché des cryptomonnaies, le POC d'un outil utilisant ces algorithmes est disponible</p>
                      </v-flex>
                      <v-flex font-italic caption xs2 text-xs-right>Depuis 10/2018</v-flex>
                    </v-layout>
                  </v-timeline-item>
                  <v-timeline-item  color="#0c907d" class="mb-3"  small>
                    <v-layout text-xs-left justify-space-between>
                      <v-flex xs10><v-subheader>Freelance (Développeur web)</v-subheader>
                      <v-card-text>J'ai effectué plusieurs missions web et ai complètement développé les sites suivants (la qualité est moyenne, le travail ancien) <br><a href="http://cosm-xskateboard.com">cosm-xskateboard.com</a>, <a href="http://helpjivan.org/">helpjivan.org</a>, <a href="http://www.aquareden.fr">aquareden.fr</a> et <a href="https://jeuduroi.fr">jeuduroi.fr</a></v-card-text></v-flex>
                      <v-flex font-italic caption xs2 text-xs-right><p>Entre 2015<br/>et 2017</p></v-flex>
                    </v-layout>
                  </v-timeline-item>
                </v-timeline>
              </v-card-text>
            </v-card>
          </v-flex>
          <v-flex xs12 text-xs-left roll-in-right>
            <v-card>
              <v-card-title>
              </v-card-title>
              <v-card-text style="padding: 0em 2.2em 2em 2.2em;">
                <v-subheader style="padding: 4px 0px 16px 0px;">
                  Qui sui-je ?
                </v-subheader>
                Passionner par la programmation je n'ai de cesse de développer mes compétences, je prendre le temps de faire du code de qualité et suis curieux, toujours a la recherche des meilleurs alternative.<br/>
                Mon atout principal est ma capacité à apprendre, pour moi utiliser une nouvelle techno, un nouveau framework ou un outil inconnu est un plaisir plus-tot qu'une corvée.</br>
                Autonome mais également très alaise en groupe je suis capable de concevoir et de développer des infrastructures complexes, adaptées et réutilisable.
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
    </transition>
  </v-container>
</template>

<script>

  export default {
    data: () => ({
      main: true,
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
          { id: 2, name: 'C#/Wpf' },
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
        name: 'Lib/Framework/Techno',
        children: [
          { id: 1, name: 'CCXT' },
          { id: 2, name: 'Vue.js' },
          { id: 3, name: 'React/Redux' },
          { id: 4, name: 'Electron/Ionic/Cordova' },
          { id: 5, name: 'Pandas/RustLearn' },
          { id: 6, name: 'SqlLite/MySql' },
          { id: 7, name: 'Open LDAP' },
          { id: 8, name: 'OpenGL/OpenCL' },
          { id: 9, name: 'Rocket/Express/Nancy' },
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

.fade-enter-active {
	-webkit-animation: slide-in-top 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) .3s both;
	        animation: slide-in-top 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) .3s both;
} 
.fade-leave-active {
	-webkit-animation: bounce-out-top 1s both;
	        animation: bounce-out-top 1s both;
}

.fade2-enter-active {
	-webkit-animation: slide-in-top 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) .3s both;
	        animation: slide-in-top 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) .3s both;
} 
.fade2-leave-active {
	-webkit-animation: bounce-out-top 1s both 10s;
	        animation: bounce-out-top 1s both 10s;
}

.bounce-in-top, .bounce-in-bottom, .roll-in-right {
	-webkit-animation: slide-in-top 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) .3s both;
	        animation: slide-in-top 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) .3s both;
}
@-webkit-keyframes bounce-out-top {
  0% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
  }
  10% {
    -webkit-transform: translateY(-10px);
            transform: translateY(-10px);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }
  20% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
  }
  85% {
    opacity: 1;
  }
  100% {
    -webkit-transform: translateY(-800px);
            transform: translateY(-800px);
    opacity: 0;
  }
}
@keyframes bounce-out-top {
  52% {
    -webkit-transform: translateY(-75px);
            transform: translateY(-75px);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }
  70% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
  }
  85% {
    opacity: 1;
  }
  100% {
    -webkit-transform: translateY(-800px);
            transform: translateY(-800px);
    opacity: 0;
  }
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

@-webkit-keyframes swing-in-top-fwd {
  0% {
    -webkit-transform: rotateX(-100deg);
            transform: rotateX(-100deg);
    -webkit-transform-origin: top;
            transform-origin: top;
    opacity: 0;
  }
  100% {
    -webkit-transform: rotateX(0deg);
            transform: rotateX(0deg);
    -webkit-transform-origin: top;
            transform-origin: top;
    opacity: 1;
  }
}
@keyframes swing-in-top-fwd {
  0% {
    -webkit-transform: rotateX(-100deg);
            transform: rotateX(-100deg);
    -webkit-transform-origin: top;
            transform-origin: top;
    opacity: 0;
  }
  100% {
    -webkit-transform: rotateX(0deg);
            transform: rotateX(0deg);
    -webkit-transform-origin: top;
            transform-origin: top;
    opacity: 1;
  }
}

.swing-in-top-fwd {
}

</style>
