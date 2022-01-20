<template>
<div>
  <appbar />
  <hello-world id="sliderServices"/>
  <skills class="mb-md-15" id="skills"/>
  <banner class="mb-md-15"  id="banner"/>
  <servicestab  id="servicestab"/> 
  <formulario  id="formulario"/>
  <content-footer  id="content-footer"/>
</div>

</template>

<script lang="ts">
  import Vue from 'vue'
  import HelloWorld from '../components/HelloWorld.vue'
  import Skills from '../components/Skills.vue'
  import Banner from '../components/Banner.vue'
  import Servicestab from '../components/Servicestab.vue'
  import Formulario from '../components/Formulario.vue'
  import ContentFooter from '../components/contentFooter.vue'
  import Appbar from '../components/Appbar.vue'

  export default Vue.extend({
    name: 'Home',

    components: {
      HelloWorld,
      Skills,
      Banner,
      Servicestab,
      Formulario,
      ContentFooter,
      Appbar,
    },
  })
</script>
