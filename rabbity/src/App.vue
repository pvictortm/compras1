<template>
  <v-app>
    <v-app-bar
      app
      color="#EEEEEE"
      dark
      class="d-flex justify-center mb-6"
    >

    <img src="../imagens/rebbity1.png" width="150">
    
      <!-- <v-spacer></v-spacer> -->

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
        color="#616161"
      >
      <div>
        <span  class="mr-2">Cadastrar Restaurante</span>
        
        
      </div>
      </v-btn>
      
      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
        color="#616161"
      >
        <span class="mr-2">Cadastrar Mercado</span>
      </v-btn>

       <v-btn 
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
        color="#616161"
       > 
        <span class="mr-2">Já sou uma loja parceira</span>

      </v-btn>
    </v-app-bar>

    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
