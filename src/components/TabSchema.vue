<template>
  <v-container>
    <v-row>
      <v-col>
        <register-form />
      </v-col>
      <v-col>
        <data-table />
      </v-col>
      <v-col>
        <register-form />
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import Vue from "vue"
import DataTable from "./DataTable.vue"
import RegisterForm from "./RegisterForm.vue"

export default Vue.extend({
  components: { RegisterForm, DataTable },
  data: () => {
    return {}
  }
})
</script>

<style></style>
