<template>
  <v-app>
    <v-main>
      <v-navigation-drawer app mini-variant expand-on-hover left>
        <v-list-item class="px-2">
          <v-list-item-avatar>
            <v-img src="https://iatkv.tmgrup.com.tr/53b006/0/0/0/0/0/0?u=https%3A%2F%2Fitkv.tmgrup.com.tr%2F2021%2F05%2F31%2Fabduroziq-ve-hasbulla-magomedov-hasbik-kimdir-kac-yasinda-abduroziq-ve-hasbullanin-boyu-ve-kilosu-kac-1622464154679.jpg&mw=616"></v-img>
          </v-list-item-avatar>

          <v-list-item-title>John Leider</v-list-item-title>
        </v-list-item>

        <v-divider></v-divider>

        <v-list nav dense>
          <v-list-item link>
            <v-list-item-icon>
              <v-icon>mdi-folder</v-icon>
            </v-list-item-icon>
            <v-list-item-title>My Files</v-list-item-title>
          </v-list-item>
          <v-list-item link>
            <v-list-item-icon>
              <v-icon>mdi-account-multiple</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Shared with me</v-list-item-title>
          </v-list-item>
          <v-list-item link>
            <v-list-item-icon>
              <v-icon>mdi-star</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Starred</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-navigation-drawer>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue"

export default Vue.extend({
  name: "App",

  data: () => ({
    //
  })
})
</script>
