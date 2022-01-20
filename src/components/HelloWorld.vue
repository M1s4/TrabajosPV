<template>
  <v-carousel hide-delimiters height="663">
    <v-carousel-item
      v-for="(item, i) in items"
      :key="i"
      :src="item.src"
      gradient="to top right, rgba(0,0,0,.80), rgba(0,0,0,.80)"
    >
      <v-row class="fill-height" align="center" justify="center">
        <v-card class=" text-md-center px-7 px-md-0 white--text" width="800" color="transparent" elevation="0">
          <p class="text-md-h3 text-h4 font-weight-bold">
            {{item.profesion}}
          </p>
          <p class="text-body-1 font-weight-light text-center">
            {{ item.text }}
          </p>
          
          <v-spacer></v-spacer>
          <div class="py-3 py-md-6 text-md-center">
            <v-btn rounded outlined class="mx-md-6 white--text font-weight-light px-8 mr-5  mr-md-13"> Solicitar </v-btn>
            <v-btn rounded class="px-8">
            <v-icon left>mdi-cellphone-sound</v-icon>  
            Llamar
            </v-btn>
          </div>
          
        </v-card>
      </v-row>
    </v-carousel-item>
  </v-carousel>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          profesion: 'ELECTRICISTA',
          src: 'https://images.pexels.com/photos/7359566/pexels-photo-7359566.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940',
          text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industrys standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
          
        },
        {
          profesion: 'JARDINERO',
          src: "https://images.pexels.com/photos/4369571/pexels-photo-4369571.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940",
          text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industrys standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
        },
        {
          profesion: 'SOPORTE TECNICO',
          src: "https://images.pexels.com/photos/159304/network-cable-ethernet-computer-159304.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940",
          text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industrys standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
        },
        {
          profesion: 'CCTV',
          src: "https://images.pexels.com/photos/430208/pexels-photo-430208.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940",
          text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industrys standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
        },
      ],
    };
  },
};
</script>