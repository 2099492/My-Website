<template>
  <div>
    <v-row>
      <HelloWorld/>
    </v-row>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  },
  data () {
    return {
      test: 'test'
    }
  }
}
</script>
