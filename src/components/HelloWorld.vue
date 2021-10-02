<template>
  <div class="pa-10">
    <v-row justify="center" align="center" class="mt-8">
      <v-col cols="12" lg="2" class="ma-10">
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
      <v-col cols="12" lg="5">
        <v-card flat>
          <v-card-title style="font-size: 200%;">
            Laurens van der Bilt
          </v-card-title>
          <v-card-text style="font-size: 150%;">
            I am a learning programmer living in Amsterdam and studying at the bit-academy.
            My hobbies include programming, gaming and hanging out with friends.
          </v-card-text>
          <v-card-title>
            You can find me on:
          </v-card-title>
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
