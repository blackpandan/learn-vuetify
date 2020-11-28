<template>

  <v-app class="red lighten-4">
    <Navbar />
    <v-content>
      <router-view></router-view>
    </v-content>
    
  </v-app>  

</template>

<script>
import Navbar from '@/components/navBar.vue'
export default {
  name: 'App',
  components: {
    Navbar
  },
  data: () => ({
    //
  }),
};
</script>
<style lang="scss">
*{
  margin: 0;
  padding: 0;
}
</style>