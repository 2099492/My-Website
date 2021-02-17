<template>
  <v-row justify="center" class="mt-8">
    <v-col cols="2" class="mr-4">
      <v-card flat>
        <v-avatar
          class="profile"
          color="grey"
          size="250"
        >
          <v-img
            :src="require('../assets/d68cefb8-a3b1-4804-a5b1-fb9477d2911a.jpg')"
          />
        </v-avatar>
      </v-card>
    </v-col>
    <v-col cols="4">
      <v-card-title>
        Laurens van der Bilt
      </v-card-title>
      <v-card-text>
        My name is Laurens van der Bilt
      </v-card-text>
    </v-col>
  </v-row>
</template>

<script>

export default {
  name: 'HelloWorld',

  data () {
    return {
      test: 'test',
      src: '/profile.jpg'
    }
  },
  mounted () {
    console.log(this.test)
  }
}
</script>
