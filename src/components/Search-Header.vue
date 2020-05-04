<template>
  <v-app>
    <div class="header-section">
      <!-- SYSTEM/STATUS BAR  -->
      <div>
        <v-system-bar dark>
          <v-spacer></v-spacer>
          <v-icon>mdi-wifi-strength-4</v-icon>
          <v-icon>mdi-signal-cellular-outline</v-icon>
          <v-icon>mdi-battery</v-icon>
          <span>12:30</span>
        </v-system-bar>
      </div>

      <!-- SEARCH APP BAR  -->

      <div>
        <v-app-bar color="primary accent-4" dense dark>
          <v-app-bar-nav-icon></v-app-bar-nav-icon>

          <v-toolbar-title>Search</v-toolbar-title>
        </v-app-bar>
      </div>
    </div>
  </v-app>
</template>
<script>
export default {};
</script>
<style lang="scss"></style>
