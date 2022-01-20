<template>
<v-container fluid class="BannerImg mt-md-15 mt-15 pa-0" app 

>
      <v-img
        src="https://images.unsplash.com/photo-1553013746-1a67c06802da?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=869&q=80"
        gradient="to top right, rgba(25,36,53,.8), rgba(25,36,53,.8)"
        height="300"
      >
          <v-card color="transparent" elevation="0" class="mx-auto my-md-15 py-5 px-10 pa-0 ma-0 text-center white--text" width="700">
       
       <p class="font-weight-black text-md-h4 text-h5">
           ¿Todavía te quedan algunas preguntas?
       </p>
       <p class="font-weight-bold text-md-h5 text-h6">
           Llámenos para una consulta gratuita al 322 6289075
       </p>
       <p class="font-weight-light text-md-body-1 text-body-2">
           Lorem ipsum dolor sit amet conse ctetur adipisicing elit
       </p>

       <v-btn color="#AA9780"  rounded class="white--text px-md-9 py-5 text-caption font-weight-black">
             enviar un correo
             <v-icon right>
                 mdi-send
             </v-icon>
       </v-btn>
  </v-card>
      </v-img>


</v-container>
</template>

<script>
export default {

}
</script>

<style>


.container.BannerImg.mt-md-15.pa-0.mb-md-15.container--fluid.app {
    margin-top:  !important;
}
</style>