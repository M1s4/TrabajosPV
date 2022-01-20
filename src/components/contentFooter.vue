<template>
  <v-sheet color="#1E1E20" elevation="1"  class="text-center pt-5 pt-md-10 px-5 px-md-0">
    <v-container class="text-center">
      <v-row no-gutters justify="center">

        <v-col cols="12" sm="6" md="3">
          <v-card
            class="pa-2 text-start white--text"
            elevation="0"
            tile
            color="transparent"
          >
            <p class="font-weight-black text-h5">EMPlEOSPV</p>
            <p
              elevation="0"
              class="text-body-2 pr-5 grey--text font-weight-light pr-11"
            >
              “Ninguno de nosotros es tan bueno como todos nosotros juntos”, Ray
              Kroc.
            </p>
          </v-card>
        </v-col>

        <v-col cols="6" md="2">
          <v-card class="pa-2 white--text" outlined tile color="transparent">
            <div class="text-start d-flex flex-column  align-start align-md-center">
              <p class="mb-0 font-weight-medium text-body-1">Explorar</p>

              <v-btn
                text
                class="font-weight-light text-caption mb-0 grey--text mt-3 px-0 px-md-3"
              >
                Contacto
              </v-btn>

              <v-btn
                text
                class="font-weight-light text-caption mb-0 grey--text pl-0 px-md-3"
              >
                Servicios
              </v-btn>

              <v-btn
                text
                class="font-weight-light text-caption mb-0 grey--text pl-0 px-md-3"
              >
                Catalogo
              </v-btn>

              <v-btn
                text
                class="font-weight-light text-caption mb-0 grey--text pl-0 px-md-3"
              >
                Registrar
              </v-btn>
            </div>
          </v-card>
        </v-col>

        <v-col cols="6" md="2">
          <v-card class="pa-2" outlined tile color="transparent">
            <p class="white--text font-weight-medium text-body-1 text-start">Direccion</p>
            <p
              elevation="0"
              class="text-body-2 text-start grey--text font-weight-light"
            >
              Paseo Díaz Ordaz S/N, Centro, 48300 Puerto Vallarta, Jal.
            </p>
          </v-card>
        </v-col>

        <v-col cols="6" md="2">
          <v-card class="pa-2 d-flex flex-column  align-start" outlined tile color="transparent">
            <p class="white--text font-weight-medium text-body-1">Siguenos</p>
            <v-btn
                text
                class="font-weight-light text-caption mb-0 grey--text px-0 "
              >
                Facebook
              </v-btn>
              <v-btn
                text
                class="font-weight-light text-caption mb-0 grey--text px-0 "
              >
                Linkedin
              </v-btn>
          </v-card>
        </v-col>

        <v-col cols="6" md="2">
          <v-card class="pa-2 d-flex flex-column  align-start " outlined tile color="transparent">
                     <p class="white--text font-weight-medium text-body-1">Legal</p>

             <v-btn
                text
                class="font-weight-light text-caption mb-0 grey--text px-0 px-md-2"
              >
                Terminos
              </v-btn>
              <v-btn
                text
                class="font-weight-light text-caption mb-0 grey--text px-0 px-md-2"
              >
                Legales
              </v-btn>
          </v-card>
        </v-col>

      </v-row>
      <p class="text-start grey--text font-weight-light text-caption mt-5">
          © 2021 Todos los derechos recervados
      </p>
    </v-container>
  </v-sheet>
</template>

<script>
export default {};
</script>

<style>
</style>