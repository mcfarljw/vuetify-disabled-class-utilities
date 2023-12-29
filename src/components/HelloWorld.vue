<template>
  <v-navigation-drawer
    :border="0"
    location="top"
    :permanent="true"
    :width="100"
  >
    <div>Navigation drawer with <code>:border="0"</code></div>
  </v-navigation-drawer>

  <v-container>
    <v-row>
      <v-col>
        <v-tabs>
          <v-tab value="one">Item One</v-tab>
          <v-tab value="two">Item Two</v-tab>
          <v-tab value="three">Item Three</v-tab>
        </v-tabs>
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <v-btn>Button</v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<script setup lang="ts">
  //
</script>
