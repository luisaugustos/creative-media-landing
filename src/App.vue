<template>
  <v-app id="upwork-design">
    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
}
</script>

<style>
#upwork-design {
  background-color: #E5E5E5;
 }
 </style>
