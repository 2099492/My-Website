<template>
  <v-app>
    <v-main>
      <top-bar></top-bar>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
import TopBar from './components/TopBar'

export default {
  name: 'App',

  components: {
    TopBar
  },

  data () {
    return {
      test: 'test'
    }
  }
}
</script>
