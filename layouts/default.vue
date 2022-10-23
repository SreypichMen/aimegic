<template>
  <v-app >
    <headerMenu />     
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
  
  </v-app>
</template>

<script>
import headerMenu from '~/components/headerMenu.vue'
export default {
    components: {
        headerMenu
    } 
}
</script>
<style>
*{
  font-family: 'Roboto Condensed', sans-serif;
}
</style>
