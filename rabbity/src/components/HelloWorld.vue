<template>
  <v-container>
  <v-card
    class="mx-auto pa-md-16 mx-lg-auto"
    outlined
    width="1000"
  >
    <p>Nome</p>
    <v-form
    ref="form"
    v-model="valid"
    lazy-validation
  >
    <v-text-field
            v-model="message4"
            label="Nome completo"
            outlined
            clearable
            full-width
    ></v-text-field>
    <p>Email</p>
    <v-text-field
            v-model="message5"
            label="E-mail"
            outlined
            clearable
    ></v-text-field>
    <p>Telefone</p>
    <v-text-field
            v-model="message6"
            label="Telefone"
            outlined
            clearable
    ></v-text-field>
    <p>Senha</p>
    <v-text-field
            v-model="message7"
            label="Senha"
            outlined
            clearable
    ></v-text-field>

     <p>Confirme a senha</p>
    <v-text-field
            v-model="message8"
            label="Confirme a senha"
            outlined
            clearable
    ></v-text-field>

    <v-btn
      color="error"
      class="mr-4"
      @click="reset"
    >
      Continuar
    </v-btn>

   
  </v-form>
  </v-card>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader',
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify',
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify',
        },
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify',
        },
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer',
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
        },
      ],
    }),
  }
</script>