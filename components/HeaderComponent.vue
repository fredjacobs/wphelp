<template>
  <v-app-bar>
    <template v-slot:append>
      <v-btn icon="mdi-heart"></v-btn>

      <v-btn icon="mdi-magnify"></v-btn>

      <v-btn icon="mdi-dots-vertical"></v-btn>
    </template>
    <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>

    <v-toolbar-title>WP HELP</v-toolbar-title>
  </v-app-bar>

  <v-navigation-drawer v-model="drawer" temporary>
    <!--  -->
  </v-navigation-drawer>
</template>

<script setup>
import { ref } from "vue";

let drawer = ref(null);
</script>
