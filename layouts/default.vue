<template>
  <v-app id="inspire">
    <!--  <v-system-bar>
      <v-spacer></v-spacer>

      <v-icon>mdi-square</v-icon>

      <v-icon>mdi-circle</v-icon>

      <v-icon>mdi-triangle</v-icon>
    </v-system-bar> -->

    <header-component />

    <v-main class="bg-grey-lighten-2">
      <slot />
    </v-main>

    <footer-component />
  </v-app>
</template>

<script setup></script>
