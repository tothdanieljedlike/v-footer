<template>
  <v-footer
    light
    height="auto">
    <v-card
      class="flex"
      flat
      tile>
      <v-card-title class="teal">
        <strong class="subheading">Ez egy példa a V-Footerhez script nélkül :P</strong>
        <v-spacer />
        <v-btn          
          class="mx-3"
          dark
          icon>          
          <v-icon size="24px">check_circle</v-icon>          
        </v-btn>
        <v-btn          
          class="mx-3"
          dark
          icon>        
          <v-icon size="24px">block</v-icon> 
        </v-btn>
        <v-btn          
          class="mx-3"
          dark
          icon>
          <v-icon size="24px">remove_circle</v-icon>          
        </v-btn>
      </v-card-title>

      <v-card-actions class="blue darken-3 justify-center">
        &copy;2018 — <strong>v-footer by TDI</strong>
      </v-card-actions>
    </v-card>
  </v-footer>
</template>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
}
.myLink {
  text-decoration: none;
}
</style>