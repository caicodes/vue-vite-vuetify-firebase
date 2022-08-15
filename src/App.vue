<script setup>
// import { firebase } from './services/firebase'
const projAppName = import.meta.env.VITE_PROJECT_APP_NAME
const siteTitle = import.meta.env.VITE_SITE_TITLE
</script>
<template>
  <v-app>
    <v-main>
      <!-- expo site -->
      {{ projAppName }}
      {{ siteTitle }}
    </v-main>
  </v-app>
</template>
