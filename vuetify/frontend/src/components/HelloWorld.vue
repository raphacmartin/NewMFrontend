<template>
  <v-container>
    <v-layout row wrap>
      <v-flex class="box" sm4>
        <p class="text-xs-center">teste teste teste teste</p>
      </v-flex>
      <v-flex class="box" sm6 :xs11="xs">
        <p class="text-xs-center">teste</p>
      </v-flex>
      <v-flex class="box" sm5>
        <p class="text-xs-center">teste</p>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
  export default {
    data: () => ({
      xs: true
    })
  }
</script>

<style>
  .box {
    border: 1px solid
  }
</style>
