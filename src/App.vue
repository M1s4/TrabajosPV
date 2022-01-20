<template>
  <v-app>
    <v-app-bar color="grey lighten-5" dark app elevation="0">
      <v-app-bar-nav-icon
        color="black"
        @click="drawer = !drawer"
      ></v-app-bar-nav-icon>
      <v-toolbar-title class="black--text font-weight-medium text-body-2">
        <v-icon color="black" small left>mdi-hammer-screwdriver</v-icon>
        TRABAJOSPV</v-toolbar-title
      >
    </v-app-bar>
    <v-sheet id="scrolling-techniques-5" class="overflow-y-auto pa-0" fluid>
      <v-container fluid class="pa-0">
        <router-view />
      </v-container>
    </v-sheet>

    <v-navigation-drawer v-model="drawer" app temporary>
      <v-list nav dense class="mt-3">
        <v-list-item-group
          v-model="group"
          active-class="deep-purple--text text--accent-4"
        >
          <v-list-item
            class="mt-5 mt-md-2"
            @click="$vuetify.goTo('#sliderServices', 900)"
          >
            <v-list-item-icon>
              <v-icon left>mdi-home</v-icon>
            </v-list-item-icon>
            <v-list-item-title>INICIO</v-list-item-title>
          </v-list-item>

          <v-list-item class="mt-5 mt-md-2"  @click="$vuetify.goTo('#formulario', 900)">
            <v-list-item-icon>
              <v-icon left>mdi-card-account-mail</v-icon>
            </v-list-item-icon>
            <v-list-item-title>CONTACTO</v-list-item-title>
          </v-list-item>

          <v-list-item class="mt-5 mt-md-2"  @click="$vuetify.goTo('#servicestab', 900)">
            <v-list-item-icon>
              <v-icon left>mdi-account-wrench</v-icon>
            </v-list-item-icon>
            <v-list-item-title>SERVICIOS</v-list-item-title>
          </v-list-item>

          <v-list-item class="mt-5 mt-md-2"  @click="$vuetify.goTo('#skills', 900)">
            <v-list-item-icon>
              <v-icon left>mdi-clipboard-list</v-icon>
            </v-list-item-icon>
            <v-list-item-title>SKILLS</v-list-item-title>
          </v-list-item>
        </v-list-item-group>
      </v-list>

      <v-divider class="mx-4 mt-9 mb-4" color="grey"></v-divider>
      <v-spacer></v-spacer>
      <template>
        <div class="px-3 pb-1">
          <v-btn block color="black" outlined class="rounded-0">
            Iniciar Sesion
          </v-btn>
        </div>
        <div class="px-3">
          <v-btn block color="black" class="white--text rounded-0">
            Registrate
          </v-btn>
        </div>
      </template>

    </v-navigation-drawer>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "App",

  data: () => ({
    drawer: false,
    group: null,
  }),
});
</script>
