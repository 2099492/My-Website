<template>
  <div class="ma-0 pa-0">
    <v-row justify="center" align="center" class="pa-10 ma-0">
      <v-col cols="7" lg="2">
        <v-card flat>
          <v-avatar
            class="profile"
            color="grey"
            size="280"
          >
            <v-img
              :src="require('../assets/d68cefb8-a3b1-4804-a5b1-fb9477d2911a.jpg')"
            />
          </v-avatar>
        </v-card>
      </v-col>
      <v-col cols="7" lg="5">
        <v-card flat>
          <v-card-text style="font-size: 200%; font-weight: bold; color: black">
            Laurens van der Bilt
          </v-card-text>
          <v-card-text style="font-size: 150%;">
            I am a learning programmer living in Amsterdam and studying at the bit-academy.
            My hobbies include programming, gaming and hanging out with friends.
          </v-card-text>
          <v-card-title>
            You can find me on:
          </v-card-title>
          <div class="pl-4">
            <a href="https://www.linkedin.com/in/laurens-van-der-bilt/" class="pr-2">
              <v-btn color="primary">
                LinkedIn
              </v-btn>
            </a>
            <a href="https://github.com/2099492">
              <v-btn color="secondary">
                GitHub
              </v-btn>
            </a>
          </div>
        </v-card>
      </v-col>
    </v-row>
  </div>
</template>

<script>

export default {
  name: 'HelloWorld',

  data () {
    return {
      test: 'test'
    }
  }
}
</script>

<style>

</style>
