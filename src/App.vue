<template>
  <v-app>
    <v-app-bar app dark color= 'purple'>
      <v-toolbar-title>OTTO KLAUS</v-toolbar-title>
      <v-spacer></v-spacer>
    <router-link to="/login">
      <v-btn text rounded>Login</v-btn></router-link>
    
      <v-btn text rounded>Home</v-btn>
      <v-btn text rounded>About</v-btn>


    </v-app-bar>
      <router-view></router-view>
 
  </v-app>
</template>

<script>

export default {
  name: 'App',

  components: {
  },

  data: () => ({
    //
  }),
};
</script>
