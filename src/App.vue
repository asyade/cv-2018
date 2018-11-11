<template>
  <v-app dark>
    <meta name="viewport" content="width=device-width, initial-scale=0.41, maximum-scale=1" />
    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      //
    }
  }
}
</script>
