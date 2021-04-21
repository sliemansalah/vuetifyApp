<template>
  <v-app :dir="direction">
    <router-view />
  </v-app>
</template>

<script>
  export default {
    data() {
      return {
        direction: 'rtl'
      }
    }
  }
</script>