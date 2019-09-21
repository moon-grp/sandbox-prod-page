<template>
  <div>
    <v-toolbar app color="brown darken-4" dark>
      <v-toolbar-title>Noansa</v-toolbar-title>

      <div class="flex-grow-1"></div>

      <v-toolbar-items>
        <v-btn text>Shop</v-btn>
        <v-btn text>Wholesale</v-btn>
        <v-btn text>Locations</v-btn>
        <v-btn text>Our Story</v-btn>
      </v-toolbar-items>

      <template v-if="$vuetify.breakpoint.smAndUp">
        <v-btn icon>
          <v-icon>mdi-magnify</v-icon>
        </v-btn>
        <v-btn icon>
          <v-icon>mdi-account</v-icon>
        </v-btn>
      </template>
    </v-toolbar>
  </div>
</template>


<script>
export default {
    name:'toolbar'
}
</script>


<style >
    
</style>