<template>
  <v-app>
    
    <HeaderBar/>
    <v-content>
      <NavigationTable/>
    </v-content>
  </v-app>
</template>

<script>
import HeaderBar from './components/Header/HeaderBar';
import NavigationTable from './components/NavigationTable';

export default {
  name: 'App',

  components: {
    NavigationTable,
    HeaderBar,
  },

  data: () => ({
    //
  }),
};
</script>
