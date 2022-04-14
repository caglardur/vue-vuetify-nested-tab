<template>
  <v-form ref="form" v-model="valid" lazy-validation>
    <v-text-field v-model="name" :counter="10" :rules="nameRules" label="Name" required></v-text-field>

    <v-text-field v-model="email" :rules="emailRules" label="E-mail" required></v-text-field>

    <v-select v-model="select" :items="items" :rules="[v => !!v || 'Item is required']" label="Item" required></v-select>

    <v-checkbox v-model="checkbox" :rules="[v => !!v || 'You must agree to continue!']" label="Do you agree?" required></v-checkbox>

    <v-btn :disabled="!valid" color="success" class="mr-4"> Validate </v-btn>

    <v-btn color="error" class="mr-4"> Reset Form </v-btn>

    <v-btn color="warning"> Reset Validation </v-btn>
  </v-form>
</template>

<script lang="ts">
import Vue from "vue"

export default Vue.extend({
  name: "RegisterForm",
  data: () => ({
    valid: true,
    name: "",
    nameRules: ["Name must be less than 10 characters"],
    email: "",
    emailRules: ["E-mail must be valid"],
    select: null,
    items: ["Item 1", "Item 2", "Item 3", "Item 4"],
    checkbox: false
  })
})
</script>
