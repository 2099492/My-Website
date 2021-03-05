<template>
  <div>
    <v-row justify="center" class="mt-8">
      <v-col cols="2" class="mr-4">
        <v-card flat>
          <v-avatar
            class="profile"
            color="grey"
            size="180"
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
          I am a learning programmer living in Amsterdam and studying at the bit-academy.
          My hobbies include programming, gaming and hanging out with friends.
        </v-card-text>
        <v-card-title>
          My skills include:
        </v-card-title>
        <h4>Coding languages:</h4>
        <v-list-item>
          <v-list-item-content>
            <v-card-text>
              JavaScript
            </v-card-text>
          </v-list-item-content>
        </v-list-item>
        <v-list-item>
          <v-list-item-content>
            <v-card-text>
              php
            </v-card-text>
          </v-list-item-content>
        </v-list-item>
        <v-list-item>
          <v-list-item-content>
            <v-card-text>
              HTML, CSS
            </v-card-text>
          </v-list-item-content>
        </v-list-item>
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
  },
  mounted () {
    console.log(this.test)
  }
}
</script>
