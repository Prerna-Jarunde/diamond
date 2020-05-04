<template>
  <div>
    <v-content>
      <searchHeader />
    </v-content>

    <v-content>
      <searchScreen />
    </v-content>
        <v-content>
      <newSearch />
    </v-content>
    <v-content>
      <searchFooter />
    </v-content>
  </div>
</template>
<script>
import searchHeader from "@/components/Search-Header.vue";

import searchScreen from "@/components/SearchScreen.vue";
import newSearch from "@/components/NewSearch.vue";
import searchFooter from "@/components/Search-Footer.vue";

export default {
  name: "MainSearch",
  components: {
    searchHeader,
   
    searchScreen,
     newSearch,
    searchFooter
  }
};
</script>
<style lang="scss"></style>
