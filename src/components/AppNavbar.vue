<script setup lang="ts">
import { useCurrentUser } from 'vuefire'
import NavItems from './NavItems.vue'

const user = useCurrentUser()
console.log(user)
</script>

<template>
  <v-app-bar color="teal">
    <v-app-bar-title>Vue Eats</v-app-bar-title>
    <v-spacer></v-spacer>
    <nav-items />
  </v-app-bar>
</template>

<style></style>
