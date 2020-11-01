<template>
<v-container>

    <form @submit.prevent="submit">

        <v-text-field
          v-model="name"
          :counter="10"
          :error-messages="errors"
          label="Name"
          required
        ></v-text-field>

        <v-text-field
          v-model="email"
          :error-messages="errors"
          label="E-mail"
          required
        ></v-text-field>
        <v-text-field
          v-model="password"
          :error-messages="errors"
          label="password"
          type="password"
          required
        ></v-text-field>


      <v-btn
        class="mr-4"
        type="submit"
        :disabled="invalid"
      >
        submit
      </v-btn>
      <v-btn @click="clear">
        clear
      </v-btn>
    </form>

</v-container>
 </template>
