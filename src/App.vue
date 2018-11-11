<template>
  <v-app dark>
    <meta name="viewport" content="width=device-width, initial-scale=0.41, maximum-scale=1" />
    <v-content>
      <Main/>
    </v-content>
  </v-app>
</template>

<script>
import Main from './components/Main'
import Skills from './components/Skills'

export default {
  name: 'App',
  components: {
    Main,
    Skills
  },
  data () {
    return {
      //
    }
  }
}
</script>
