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

    <v-footer
    color="#EEEEEE"
    padless
    
    >
    <v-row
      app
      class="d-flex justify-space-around mb-6"
      no-gutters
      text
    >
    

    
    
      <div>
        <h1 class="mr-2 red--text">
          Serviços
        </h1>
        <a class="mb-7">App Delivery</a><br>
        <a class="mb-7">Gestor de Pedidos</a><br>
        <a class="mb-7">App Entregador</a><br>
        <a class="mb-7">App Dashboard</a><br>
      </div>

      <div>
        <h1 class="mr-2 red--text">
          Sobre
        </h1>
        <a class="mb-7">Política de Cookies</a><br>
        <a class="mb-7">Política de Privacidade</a><br>
        <a class="mb-7">Termos</a><br>
      </div>
      
       <div>
        <h1 class="mr-2 red--text">
          Rebbity
        </h1>
        <a>
          Usando tecnologia pra alimentar todos por um valor mais justo. <br> Quem pede na Rebbity tem tdo na palma da mão, pra qualquer hora e lugar.
        </a>
      </div>
   
    </v-row>


  </v-footer>
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
    links: [
        'Serviços',
        'Sobre',
        'Rebbity',
      ],
  }),
};
</script>
