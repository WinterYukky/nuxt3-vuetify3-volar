<template>
  <v-app>
    <v-app-bar app>
      <v-app-bar-title>Nuxt3 & Vuetify3 & Volar project</v-app-bar-title>
    </v-app-bar>
    <v-main>
      <v-dialog>
        <template #activator="{ isActive }"></template>
      </v-dialog>
      <nuxt-page></nuxt-page>
    </v-main>
  </v-app>
</template>
