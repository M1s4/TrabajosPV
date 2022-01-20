<template>
  <v-sheet fluid class="mt-md-15 mb-md-15">
    <v-row no-gutters class="d-flex flex-column flex-md-row">
      <v-col col="12" sm="6" md="2">
        <v-card class="pa-0" elevation="0">
          <v-btn class="mt-15 mb-6 rounded-0 py-md-6" color="#BB593B"  @click="$vuetify.goTo('#sliderServices', 900)">
            <v-icon color="white" large> mdi-chevron-up </v-icon>
          </v-btn>
        </v-card>
      </v-col>
      <v-col col="12" md="6">
        <v-card class="px-0 px-md-15" elevation="0">
          <components-form />
        </v-card>
      </v-col>
      <v-col col="12" md="4">
        <v-card class="pa-0 ml-md-10 mt-10 mt-md-0" elevation="0">

          <v-overlay absolute color="transparent" class="d-none d-md-block mt-md-15">
            <v-card
              color="#1E1E20"
              class="                
                px-7
                pt-6
                pb-1
                px-md-15
                py-md-15
                grey--text
                rounded-0
                mt-md-3
              "
              max-width="450"
              min-width="350"
              elevation="0"
            >
              <p class="font-weight-black text-h5 white--text">INFORMACION</p>
              <div class="pl-2">
                <p class="font-weight-light py-2 text-body-2">
                  <v-icon color="grey" small left>
                    mdi-map-marker-outline
                  </v-icon>
                  Puerto Vallarta, Jalisco Mexico
                </p>
                <p class="font-weight-light py-2 text-body-2">
                  <v-icon color="grey" small left> mdi-email </v-icon>
                  correoempresa@gmail.com
                </p>
                <p class="font-weight-light py-2 text-body-2">
                  <v-icon color="grey" small left> mdi-phone </v-icon>
                  3221236598
                </p>
                <p class="font-weight-light py-2 text-body-2">
                  <v-icon color="grey" small left> mdi-clock </v-icon>
                  00:00 am - 00:00 pm
                </p>
              </div>
            </v-card>
          </v-overlay>

          <v-card
            color="#BB593B"
            height="550"
            width="115"
            class="ml-auto rounded-0 d-none d-md-block"
          >
            <v-btn absolute bottom text class="pa-0 ma-0">
              <v-icon color="white" small>mdi-facebook</v-icon>
            </v-btn>
            <v-btn absolute bottom text class="pa-0 ma-0" right>
              <v-icon color="white" small> mdi-whatsapp </v-icon>
            </v-btn>
          </v-card>
        </v-card>
      </v-col>
    </v-row>
  </v-sheet>
</template>

<script>
import ComponentsForm from "../components/ComponentsForm.vue";

export default {
  components: {
    ComponentsForm,
  },
};
</script>

<style>
.DataForm {
 
}
</style>