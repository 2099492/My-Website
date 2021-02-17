<template>
  <v-row justify="center">
    <v-col cols="3">
      <v-tabs>
        <v-tab @click="$router.push({ name: 'Home' })">Home</v-tab>
        <v-tab @click="$router.push({ name: 'About' })">Info</v-tab>
      </v-tabs>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'TopBar',

  data () {
    return {
      test: 'test'
    }
  },
  mounted () {
    console.log(this.test)
  }
}
</script>
