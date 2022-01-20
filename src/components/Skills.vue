<template>
  <v-sheet
    class="sliderSkill "
    elevation="0"
    max-width="900"
    min-width="auto"
    color="transparent"
  >
    <v-slide-group v-model="model" class="px-3">

      <v-slide-item >
        <v-hover v-slot="{ hover }">
          <v-card
            class="mx-md-2"
            color="grey lighten-4"
            max-width="600"
            width="200"
            height="200"
          >
            <div >
              <v-card  class="d-flex flex-column justify-center text-center" color="#192435" height="200">
                <v-icon large color="white" class="pb-3"> mdi-handshake-outline </v-icon>
                <p class="font-weight-light white--text" >CONFIANZA</p>
                
              </v-card>
              <v-expand-transition>
                <div
                  v-if="hover"
                  class="
                    d-flex
                    transition-fast-in-fast-out
                    grey lighten-5
                    v-card--reveal
                    text-body-2
                    text-center                    
                    px-4                    
                  "
                  style="height: 100%"
                >
                  It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.
                </div>
              </v-expand-transition>
            </div>
          </v-card>
        </v-hover>
      </v-slide-item>

      <v-slide-item >
        <v-hover v-slot="{ hover }">
          <v-card
            class="mx-2"
            color="grey lighten-4"
            max-width="600"
            width="200"
            height="200"
          >
            <div >
              <v-card  class="d-flex flex-column justify-center text-center" color="#192435" height="200">
                <v-icon large color="white" class="py-3"> mdi-shield-home </v-icon>
                <p class="font-weight-light white--text" >SEGURIDAD</p>
                
              </v-card>
              <v-expand-transition>
                <div
                  v-if="hover"
                  class="
                    d-flex
                    transition-fast-in-fast-out
                    grey lighten-5
                    v-card--reveal
                    text-body-2
                    text-center                    
                    px-4   
                  "
                  style="height: 100%"
                >
                  It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.
                </div>
              </v-expand-transition>
            </div>
          </v-card>
        </v-hover>
      </v-slide-item>

      <v-slide-item >
        <v-hover v-slot="{ hover }">
          <v-card
            class=""
            color="grey lighten-4"
            max-width="600"
            width="200"
            height="200"
          >
            <div >
              <v-card  class="d-flex flex-column justify-center text-center" color="#192435" height="200">
                <v-icon large color="white" class="py-3"> mdi-calendar-clock </v-icon>
                <p class="font-weight-light white--text" >SENCILLO</p>
                
              </v-card>
              <v-expand-transition>
                <div
                  v-if="hover"
                  class="
                    d-flex
                    transition-fast-in-fast-out
                    grey lighten-5
                    v-card--reveal
                    text-body-2
                    text-center                    
                    px-4   
                  "
                  style="height: 100%"
                >
                  It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.
                </div>
              </v-expand-transition>
            </div>
          </v-card>
        </v-hover>
      </v-slide-item>

      <v-slide-item >
        <v-hover v-slot="{ hover }">
          <v-card
            class="mx-2"
            color="grey lighten-4"
            max-width="600"
            width="200"
            height="200"
          >
            <div >
              <v-card  class="d-flex flex-column justify-center text-center" color="#192435" height="200">
                <v-icon large color="white" class="py-3"> mdi-account-hard-hat </v-icon>
                <p class="font-weight-light white--text" >EXPERIENCIA</p>
                
              </v-card>
              <v-expand-transition>
                <div
                  v-if="hover"
                  class="
                    d-flex
                    transition-fast-in-fast-out
                    grey lighten-5
                    v-card--reveal
                    text-body-2
                    text-center                    
                    px-4   
                  "
                  style="height: 100%"
                >
                  It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.
                </div>
              </v-expand-transition>
            </div>
          </v-card>
        </v-hover>
      </v-slide-item>

    </v-slide-group>
  </v-sheet>
</template>

<script>
export default {
  data: () => ({
    model: null,
  }),
};
</script>

<style>
.sliderSkill {
  margin-left: auto;
  margin-right: auto;
  margin-top: -120px;
  z-index: 3;
  left: 20%;
}
.BgNone {
  background-color: transparent !important;
}
.v-card--reveal {
  align-items: center;
  bottom: 0;
  justify-content: center;
  opacity: 0.89;
  position: absolute;
  width: 100%;
}
</style>