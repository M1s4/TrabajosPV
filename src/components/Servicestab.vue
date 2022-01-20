<template>
  <v-card class="mt-10 mt-md-0">
    <v-sheet class="text-center mx-auto pb-md-5 " max-width="700">
      <p class="font-weight-black text-md-h4 text-h5">NUESTROS SERVICIOS</p>
      <p class="text-body-1">
        There are many variations of passages of Lorem Ipsum available, but the
        majority have suffered alteration in some form
      </p>
    </v-sheet>

    <v-tabs centered>
      <v-tab class="black--text px-md-10">
        <v-icon left color="black"> mdi-lightning-bolt</v-icon>
        <p class="font-weight-black text-caption mb-0">ELECTRICISTA</p>
      </v-tab>

      <v-tab class="black--text px-md-10">
        <v-icon left color="black"> mdi-shovel</v-icon>
        <p class="font-weight-black text-caption mb-0">JARDINERO</p>
      </v-tab>

      <v-tab class="black--text px-md-10">
        <v-icon left color="black"> mdi-desktop-classic</v-icon>
        <p class="font-weight-black text-caption mb-0">SOPORTE TECNICO</p>
      </v-tab>

      <v-tab class="black--text px-md-10">
        <v-icon left color="black"> mdi-cctv</v-icon>
        <p class="font-weight-black text-caption mb-0">CCTV</p>
      </v-tab>

      <v-tab-item>
        <v-card  class="mt-5" elevation="0 ">
          <v-row no-gutters>
            <v-col cols="12" sm="6" md="5" class="d-none d-md-inline ">
              <v-card class="pa-0" >
                <v-img
                  lazy-src="https://picsum.photos/id/11/10/6"
                  height="500"
                  src="https://images.pexels.com/photos/7359566/pexels-photo-7359566.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
                ></v-img>
              </v-card>
            </v-col>
            <v-col xs="4" cols="12" md="7">
              <v-card class="pa-0" >
                <v-img
                  src="https://images.unsplash.com/photo-1566417110090-6b15a06ec800?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=774&q=80"
                  gradient="to top right, rgba(25,36,53,.9), rgba(25,36,53,.9)" 
                  height="500"                 
                >
                  <v-sheet
                    max-width="500"
                    height="400"
                    class="mx-auto mt-md-8 pt-9 pt-md-3 white--text px-10 "
                    color="transparent"
                  >
                    <p class="font-weight-bold text-h5 ">ELECTRICISTA</p>
                    <div class="d-flex flex-column flex-md-row mt-md-3">
                      <v-icon size="80" color="white" left class="d-none d-md-block">
                        mdi-home-lightning-bolt
                      </v-icon>
                      <p class="mb-0 ">
                        It is a long established fact that a reader will be
                        distracted by the readable content of a page when
                        looking at its layout.
                      </p>
                    </div>
                    <div class="mt-9">
                      <p class="font-weight-light">
                        <v-icon left color="white">mdi-check-all</v-icon>
                        It is a long established fact that a reader will be
                        distracted
                      </p>
                      <p class="font-weight-light">
                        <v-icon left color="white">mdi-check-all</v-icon>
                        It is a long established fact that a reader will be
                        distracted
                      </p>
                      <p class="font-weight-light">
                        <v-icon left color="white">mdi-check-all</v-icon>
                        It is a long established fact that a reader will be
                        distracted
                      </p>
                    </div>
                    <v-btn class="text-caption font-weight-black mt-9 px-9 py-5" rounded>
                        <v-icon left>mdi-phone</v-icon>
                        LLAMA Y AGENDA TU CITA
                    </v-btn>
                  </v-sheet>
                </v-img>
              </v-card>
            </v-col>
          </v-row>
        </v-card>
      </v-tab-item>

      <v-tab-item>
        <v-card flat class="mt-5">
          <v-row no-gutters>
            <v-col cols="12" sm="6" md="5" class="d-none d-md-inline">
              <v-card class="pa-0" >
                <v-img
                  lazy-src="https://picsum.photos/id/11/10/6"
                  height="500"
                  src="https://images.pexels.com/photos/4369571/pexels-photo-4369571.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
                ></v-img>
              </v-card>
            </v-col>
            <v-col xs="4" cols="12" md="7">
              <v-card class="pa-0" >
                <v-img
                  src="https://images.unsplash.com/photo-1523301551780-cd17359a95d0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=773&q=80"
                  gradient="to top right, rgba(25,36,53,.9), rgba(25,36,53,.9)"

                  height="500"
                >
                  <v-sheet
                    max-width="500"
                    class="mx-auto mt-md-8 pt-9 pt-md-0 white--text px-10"
                    color="transparent"
                  >
                    <p class="font-weight-bold text-h5 ">JARDINERO</p>
                    <div class="d-flex flex-column flex-md-row mt-md-3">
                      <v-icon size="80" color="white" left class="d-none d-md-block">
                        mdi-shovel
                      </v-icon>
                      <p class="mb-0 ">
                        It is a long established fact that a reader will be
                        distracted by the readable content of a page when
                        looking at its layout.
                      </p>
                    </div>
                    <div class="mt-9">
                      <p class="font-weight-light">
                        <v-icon left color="white">mdi-check-all</v-icon>
                        It is a long established fact that a reader will be
                        distracted
                      </p>
                      <p class="font-weight-light">
                        <v-icon left color="white">mdi-check-all</v-icon>
                        It is a long established fact that a reader will be
                        distracted
                      </p>
                      <p class="font-weight-light">
                        <v-icon left color="white">mdi-check-all</v-icon>
                        It is a long established fact that a reader will be
                        distracted
                      </p>
                    </div>
                    <v-btn class="text-caption font-weight-black mt-9 px-9 py-5" rounded>
                        <v-icon left>mdi-phone</v-icon>
                        LLAMA Y AGENDA TU CITA
                    </v-btn>
                  </v-sheet>
                </v-img>
              </v-card>
            </v-col>
          </v-row>
        </v-card>
      </v-tab-item>

     <v-tab-item>
        <v-card  class="mt-5">
          <v-row no-gutters>
            <v-col cols="12" sm="6" md="5" class="d-none d-md-inline">
              <v-card class="pa-0" outlined tile>
                <v-img
                  lazy-src="https://picsum.photos/id/11/10/6"
                  height="500"
                  src="https://images.pexels.com/photos/159304/network-cable-ethernet-computer-159304.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
                ></v-img>
              </v-card>
            </v-col>
            <v-col cols="12" md="7">
              <v-card class="pa-0" >
                <v-img
                  src="https://images.unsplash.com/photo-1550548151-273c31c7edfb?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=869&q=80"
                  gradient="to top right, rgba(25,36,53,.9), rgba(25,36,53,.9)"
                  height="500"
                >
                   <v-sheet
                    max-width="500"
                    class="mx-auto mt-md-8 pt-9 pt-md-0 white--text px-10"
                    color="transparent"
                  >
                    <p class="font-weight-bold text-h5 ">SOPORTE TECNICO</p>
                    <div class="d-flex flex-column flex-md-row mt-md-3">
                      <v-icon size="80" color="white" left class="d-none d-md-block">
                        mdi-face-agent
                      </v-icon>
                      <p class="mb-0 ">
                        It is a long established fact that a reader will be
                        distracted by the readable content of a page when
                        looking at its layout.
                      </p>
                    </div>
                    <div class="mt-9">
                      <p class="font-weight-light">
                        <v-icon left color="white">mdi-check-all</v-icon>
                        It is a long established fact that a reader will be
                        distracted
                      </p>
                      <p class="font-weight-light">
                        <v-icon left color="white">mdi-check-all</v-icon>
                        It is a long established fact that a reader will be
                        distracted
                      </p>
                      <p class="font-weight-light">
                        <v-icon left color="white">mdi-check-all</v-icon>
                        It is a long established fact that a reader will be
                        distracted
                      </p>
                    </div>
                    <v-btn class="text-caption font-weight-black mt-9 px-9 py-5" rounded>
                        <v-icon left>mdi-phone</v-icon>
                        LLAMA Y AGENDA TU CITA
                    </v-btn>
                  </v-sheet>
                </v-img>
              </v-card>
            </v-col>
          </v-row>
        </v-card>
      </v-tab-item>

      <v-tab-item>
        <v-card flat class="mt-5">
          <v-row no-gutters>
            <v-col cols="12" sm="6" md="5" class="d-none d-md-inline">
              <v-card class="pa-0" outlined tile>
                <v-img
                  lazy-src="https://picsum.photos/id/11/10/6"
                  height="500"
                  src="https://images.unsplash.com/photo-1617897711385-df9c86b7dfe3?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80"
                ></v-img>
              </v-card>
            </v-col>
            <v-col cols="12" md="7">
              <v-card class="pa-0" >
                <v-img
                  src="https://images.unsplash.com/photo-1530476853990-25a9c69b8917?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1031&q=80"
                  gradient="to top right, rgba(25,36,53,.9), rgba(25,36,53,.9)"
                  height="500"
                >
                   <v-sheet
                    max-width="500"
                    class="mx-auto mt-md-8 pt-9 pt-md-0 white--text px-10"
                    color="transparent"
                  >
                    <p class="font-weight-bold text-h5 ">SOPORTE TECNICO</p>
                    <div class="d-flex flex-column flex-md-row mt-md-3">
                      <v-icon size="80" color="white" left class="d-none d-md-block">
                        mdi-cctv
                      </v-icon>
                      <p class="mb-0 ">
                        It is a long established fact that a reader will be
                        distracted by the readable content of a page when
                        looking at its layout.
                      </p>
                    </div>
                    <div class="mt-9">
                      <p class="font-weight-light">
                        <v-icon left color="white">mdi-check-all</v-icon>
                        It is a long established fact that a reader will be
                        distracted
                      </p>
                      <p class="font-weight-light">
                        <v-icon left color="white">mdi-check-all</v-icon>
                        It is a long established fact that a reader will be
                        distracted
                      </p>
                      <p class="font-weight-light">
                        <v-icon left color="white">mdi-check-all</v-icon>
                        It is a long established fact that a reader will be
                        distracted
                      </p>
                    </div>
                    <v-btn class="text-caption font-weight-black mt-9 px-9 py-5" rounded>
                        <v-icon left>mdi-phone</v-icon>
                        LLAMA Y AGENDA TU CITA
                    </v-btn>
                  </v-sheet>
                </v-img>
              </v-card>
            </v-col>
          </v-row>
        </v-card>
      </v-tab-item>
    </v-tabs>
  </v-card>
</template>