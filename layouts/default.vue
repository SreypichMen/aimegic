<template>
  
  <v-app class="layout">
    <headerMenu />     

        <Nuxt />
  
  
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
.layout{
  /*font-family: 'Roboto Condensed', sans-serif;*/
  /* font-family: 'Jost', sans-serif; 
  font-family: 'Fasthand', cursive;*/
  font-family: "Haas Grot Text R Web", "Helvetica Neue", Helvetica, Arial, sans-serif;
}
</style>
