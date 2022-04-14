<template>
  <v-col class="pa-0">
    <v-tabs v-model="tab" background-color="primary" dark fixed class="sticky">
      <v-tab>DataTable</v-tab>
      <v-tab v-for="item in items" :key="item.tab">
        {{ item.tab }}
      </v-tab>
    </v-tabs>
    <v-tabs-items v-model="tab">
      <v-tab-item>
        <v-card>
          <data-table @eventName="addTab" />
        </v-card>
      </v-tab-item>
      <v-tab-item v-for="item in items" :key="item.tab">
        <v-card raised>
          <tab-schema />
        </v-card>
      </v-tab-item>
    </v-tabs-items>
  </v-col>
</template>

<script lang="ts">
import Vue from "vue"
import { VListItemSubtitle } from "vuetify/lib"
import DataTable from "./DataTable.vue"
import TabSchema from "./TabSchema.vue"

export default Vue.extend({
  components: { DataTable, TabSchema },
  data: function () {
    return {
      tab: null,
      items: [
        { tab: "One", content: "Tab 1 Content" },
        { tab: "Two", content: "Tab 2 Content" }
      ]
    }
  },
  methods: {
    addTab(event: { tab: string; content: string }) {
      console.log("addtab", event)
      this.items.push(event)
    }
  }
})
</script>
<style scoped>
.sticky {
  position: sticky;
  top: 0;
  z-index: 1;
}
</style>
