<template>
  <v-app>
    <v-app-bar>
    </v-app-bar>
    <v-main>
      <CalendarVue/>
    </v-main>
  </v-app>
</template>

<script>
import CalendarVue from './components/Calendar.vue';

export default {
  name: 'App',

  components: {
    CalendarVue
  },

  data: () => ({
    //
  }),
};
</script>
